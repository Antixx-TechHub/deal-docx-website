<template>
    <div>
        <Navbar class="navbar-style-two" />
        <PageHeader />
        <Partner />
        <Blog class="pt-0" />
        <Faq />
        <!-- <Stats /> -->
        <!-- <IAQSolutions /> -->
        <!-- <ChallengesAndTrack /> -->
        <!-- <FreeTrial /> -->
        <FooterStyleFour />
    </div>
</template>

<script>
import Navbar from '../Layout/Navbar'
import PageHeader from '../ContactUs/PageHeader'
import Partner from '../Common/Partner'
import Blog from '../Common/Blog'
import Faq from '../HomePage/Faq'
// import IAQSolutions from '../ContactUs/IAQSolutions'
// import ChallengesAndTrack from '../CPQIntegration/ChallengesAndTrack'
// import Stats from '../ContactUs/Stats'
// import FreeTrial from '../ContactUs/FreeTrial'
import FooterStyleFour from '../Layout/FooterStyleFour'

export default {
    name: 'AboutUs',
    components: {
        Navbar,
        PageHeader,
        Partner,
        Blog,
        Faq,
        // IAQSolutions,
        // ChallengesAndTrack,
        // Stats,
        // FreeTrial,
        FooterStyleFour,
    }
}
</script>