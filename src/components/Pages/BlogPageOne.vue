<template>
    <div>
        <Navbar class="navbar-style-two" />
        <PageTitle class="page-title-style-two" pageTitle="Blog Right Sidebar" />
        <Blog />
        <Footer />
    </div>
</template>

<script>
import Navbar from '../Layout/Navbar'
import PageTitle from '../Common/PageTitle'
import Blog from '../BlogOne/Blog'
import Footer from '../Layout/Footer'

export default {
    name: 'BlogPageOne',
    components: {
        Navbar,
        PageTitle,
        Blog,
        Footer,
    }
}
</script>