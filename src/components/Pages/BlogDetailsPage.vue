<template>
    <div>
        <Navbar class="navbar-style-two"/>
        <PageTitle class="page-title-style-two"
            v-if="details !== null"
            :pageTitle="details[0].attributes.title" 
        />
        <div v-if="details !== null">
            <BlogDetails 
                v-bind:detailsContent="details"
            />
        </div>
        <Footer />
    </div>
</template>

<script>
import axios from 'axios'
import Navbar from '../Layout/Navbar'
import PageTitle from '../Common/PageTitle'
import BlogDetails from '../BlogDetails/BlogDetails'
import Footer from '../Layout/FooterStyleFour'

export default {
    name: 'BlogPageOne',
    components: {
        Navbar,
        PageTitle,
        BlogDetails,
        Footer,
    },
    data (){
        return {
            details: null
        }
    },
    created: async function (){
        const { slug } = this.$route.params
        const reaponse = await axios.get(`http://cms.dealdox.io/api/blogs?filters[slug][$eq]=${slug}&populate=*`, { params: { slug }})
        this.details = reaponse.data.data
    }
}
</script>