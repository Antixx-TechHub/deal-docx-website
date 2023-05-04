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
import PageHeader from '../LightningFastQuoteApprovals/PageHeader'
import ChallengesAndTrack from '../LightningFastQuoteApprovals/ChallengesAndTrack'
import Stats from '../LightningFastQuoteApprovals/Stats'
import FreeTrial from '../LightningFastQuoteApprovals/FreeTrial'
import FooterStyleFour from '../Layout/FooterStyleFour'

export default {
    name: 'LightningFastQuoteApprovals',
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