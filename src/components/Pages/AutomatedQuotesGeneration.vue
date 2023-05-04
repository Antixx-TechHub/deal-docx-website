<template>
    <div>
        <Navbar class="navbar-style-two" />
        <PageHeader />
        <ChallengesAndTrack />
        <Stats />
        <FreeTrial />
        <FooterStyleFour />
    </div>
</template>

<script>
import Navbar from '../Layout/Navbar'
import PageHeader from '../AutomatedQuotesGeneration/PageHeader'
import ChallengesAndTrack from '../AutomatedQuotesGeneration/ChallengesAndTrack'
import Stats from '../AutomatedQuotesGeneration/Stats'
import FreeTrial from '../AutomatedQuotesGeneration/FreeTrial'
import FooterStyleFour from '../Layout/FooterStyleFour'

export default {
    name: 'AutomatedQuotesGeneration',
    components: {
        Navbar,
        PageHeader,
        ChallengesAndTrack,
        Stats,
        FreeTrial,
        FooterStyleFour,
    }
}
</script>