<template>
    <div>
        <Navbar class="navbar-style-two" />
        <!-- <PageHeader /> -->
        <Stats />
        <IAQSolutions />
        <OurTeam />
        <Feedback />
        <Partner />
        <Blog />
        <AppDownload />
        <FooterStyleFour />
    </div>
</template>

<script>
import Navbar from '../Layout/Navbar'
// import PageHeader from '../AboutUs/PageHeader'
import IAQSolutions from '../AboutUs/IAQSolutions'
import OurTeam from '../AboutUs/OurTeam'
import Feedback from '../AboutUs/Feedback'
import Partner from '../Common/Partner'
import Blog from '../Common/Blog'
import Stats from '../AboutUs/Stats'
import AppDownload from '../HomePage/AppDownload'
import FooterStyleFour from '../Layout/FooterStyleFour'

export default {
    name: 'AboutUs',
    components: {
        Navbar,
        // PageHeader,
        IAQSolutions,
        OurTeam,
        Feedback,
        Partner,
        Blog,
        Stats,
        AppDownload,
        FooterStyleFour,
    }
}
</script>