<template>
    <div>
        <Navbar />
        <MainBanner />
        <Partner />
        <Video />
        <Features />
        <GettingBestApp />
        <IncludedBestFeatures />
        <ChallengesAndTrack />
        <AppDownload />
        <Screenshots />
        <SoftwareIntegrations />
        <Pricing />
        <CustomerReviews />
        <FreeTrial />
        <FooterStyleFour />
    </div>
</template>

<script>
import Navbar from '../Layout/Navbar'
import MainBanner from '../HomeFour/MainBanner'
import Partner from '../Common/Partner'
import Video from '../Common/Video'
import Features from '../HomeFour/Features'
import GettingBestApp from '../HomeFour/GettingBestApp'
import IncludedBestFeatures from '../HomeFour/IncludedBestFeatures'
import ChallengesAndTrack from '../HomeFour/ChallengesAndTrack'
import AppDownload from '../HomeFour/AppDownload'
import Screenshots from '../HomeFour/Screenshots'
import SoftwareIntegrations from '../HomeFour/SoftwareIntegrations'
import Pricing from '../HomeFour/Pricing'
import CustomerReviews from '../HomeFour/CustomerReviews'
import FreeTrial from '../HomeFour/FreeTrial'
import FooterStyleFour from '../Layout/FooterStyleFour'

export default {
    name: 'HomePageFour',
    components: {
        Navbar,
        MainBanner,
        Partner,
        Video,
        Features,
        GettingBestApp,
        IncludedBestFeatures,
        ChallengesAndTrack,
        AppDownload,
        Screenshots,
        SoftwareIntegrations,
        Pricing,
        CustomerReviews,
        FreeTrial,
        FooterStyleFour,
    }
}
</script>