<template>
    <div>
        <Navbar class="navbar-style-two" />
        <PageTitle class="page-title-style-two" pageTitle="Blog Right Sidebar" />
        <BlogDetails />
        <Footer />
    </div>
</template>

<script>
import Navbar from '../Layout/Navbar'
import PageTitle from '../Common/PageTitle'
import BlogDetails from '../BlogDetails/BlogDetails'
import Footer from '../Layout/Footer'

export default {
    name: 'BlogPageOne',
    components: {
        Navbar,
        PageTitle,
        BlogDetails,
        Footer,
    }
}
</script>