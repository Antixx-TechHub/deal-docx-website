<template>
    <div>
        <Navbar class="navbar-style-two" />
        <MainBanner />
        <Stats />
        <IAQSolutions />
        <ChallengesAndTrack />
        <FreeTrial />
        <FooterStyleFour />
    </div>
</template>

<script>
import Navbar from '../Layout/Navbar'
import MainBanner from '../AboutOne/MainBanner'
import IAQSolutions from '../AboutOne/IAQSolutions'
import ChallengesAndTrack from '../AboutOne/ChallengesAndTrack'
import Stats from '../AboutOne/Stats'
import FreeTrial from '../AboutOne/FreeTrial'
import FooterStyleFour from '../Layout/FooterStyleFour'

export default {
    name: 'AboutPageOne',
    components: {
        Navbar,
        MainBanner,
        IAQSolutions,
        ChallengesAndTrack,
        Stats,
        FreeTrial,
        FooterStyleFour,
    }
}
</script>