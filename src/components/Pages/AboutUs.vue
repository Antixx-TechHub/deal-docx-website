<template>
    <div>
        <Navbar class="navbar-style-two" />
        <PageHeader />
        <Stats />
        <IAQSolutions />
        <!-- <ChallengesAndTrack /> -->
        <FreeTrial />
        <FooterStyleFour />
    </div>
</template>

<script>
import Navbar from '../Layout/Navbar'
import PageHeader from '../AboutUs/PageHeader'
import IAQSolutions from '../AboutUs/IAQSolutions'
// import ChallengesAndTrack from '../CPQIntegration/ChallengesAndTrack'
import Stats from '../AboutUs/Stats'
import FreeTrial from '../AboutUs/FreeTrial'
import FooterStyleFour from '../Layout/FooterStyleFour'

export default {
    name: 'AboutUs',
    components: {
        Navbar,
        PageHeader,
        IAQSolutions,
        // ChallengesAndTrack,
        Stats,
        FreeTrial,
        FooterStyleFour,
    }
}
</script>