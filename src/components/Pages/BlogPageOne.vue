<template>
    <div>
        <Navbar class="navbar-style-two" />
        <PageTitle class="page-title-style-two" pageTitle="Blog Right Sidebar" />
        <Blog />
        <FooterStyleFour />
    </div>
</template>

<script>
import Navbar from '../Layout/Navbar'
import PageTitle from '../Common/PageTitle'
import Blog from '../BlogOne/Blog'
import FooterStyleFour from '../Layout/FooterStyleFour'

export default {
    name: 'BlogPageOne',
    components: {
        Navbar,
        PageTitle,
        Blog,
        FooterStyleFour,
    }
}
</script>