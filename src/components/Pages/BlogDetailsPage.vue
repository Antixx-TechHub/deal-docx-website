<template>
    <div>
        <Navbar />
        <PageTitle 
            v-if="details !== null"
            :pageTitle="details[0].attributes.title" 
        />
        <div v-if="details !== null">
            <BlogDetails 
                v-bind:detailsContent="details"
            />
        </div>
        <FooterStyleFour />
    </div>
</template>

<script>
import axios from 'axios'
import Navbar from '../Layout/Navbar'
import PageTitle from '../Common/PageTitle'
import BlogDetails from '../BlogDetails/BlogDetails'
import FooterStyleFour from '../Layout/FooterStyleFour'

export default {
    name: 'BlogPageOne',
    components: {
        Navbar,
        PageTitle,
        BlogDetails,
        FooterStyleFour,
    },
    data (){
        return {
            details: null
        }
    },
    created: async function (){
        const { slug } = this.$route.params
        const reaponse = await axios.get(`https://cms.antixxtechhub.in/api/blogs?filters[slug][$eq]=${slug}&populate=*`, { params: { slug }})
        this.details = reaponse.data.data
    }
}
</script>