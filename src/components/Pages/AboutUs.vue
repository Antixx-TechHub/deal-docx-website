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
        <SoftwareIntegrations />
        <FreeTrial />
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
import SoftwareIntegrations from '../AboutUs/SoftwareIntegrations'
import FreeTrial from '../AboutUs/FreeTrial'
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
        SoftwareIntegrations,
        FreeTrial,
        FooterStyleFour,
    }
}
</script>