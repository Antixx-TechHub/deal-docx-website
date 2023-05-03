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
import PageHeader from '../CPQIntegration/PageHeader'
import IAQSolutions from '../CPQIntegration/IAQSolutions'
// import ChallengesAndTrack from '../CPQIntegration/ChallengesAndTrack'
import Stats from '../CPQIntegration/Stats'
import FreeTrial from '../CPQIntegration/FreeTrial'
import FooterStyleFour from '../Layout/FooterStyleFour'

export default {
    name: 'CPQIntegration',
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