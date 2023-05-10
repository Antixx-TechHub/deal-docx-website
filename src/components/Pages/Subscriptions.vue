<template>
    <div>
        <Navbar class="navbar-style-two" />
        <MainBanner />
        <!-- <Screenshots /> -->
        <Partner />
        <SoftwareIntegrations />
        <IncludedBestFeatures />
        <Pricing />
        <FreeTrial />
        <AppDownload />
        <Faq />
        <!-- <GettingBestApp /> -->
        <!-- <Features /> -->
        <!-- <Video /> -->
        <!-- <IncludedBestFeatures /> -->
        <!-- <AppScreens /> -->
        <!-- <CustomerReviews class="bg-F4F8FC" /> -->
        <!-- <Blog /> -->
        <FooterStyleFour />
    </div>
</template>

<script>
// import TopHeader from '../Layout/TopHeader'
import Navbar from '../Layout/Navbar'
import MainBanner from '../Subscription/MainBanner'
// import Screenshots from '../HomePage/Screenshots'
import Partner from '../Subscription/Partner'
import IncludedBestFeatures from '../Subscription/IncludedBestFeatures'
// import GettingBestApp from '../HomePage/GettingBestApp'
// import Features from '../HomePage/Features'
// import Video from '../Common/Video'
// import IncludedBestFeatures from '../HomePage/IncludedBestFeatures'
// import AppScreens from '../HomePage/AppScreens'
import SoftwareIntegrations from '../Subscription/SoftwareIntegrations'
import FreeTrial from '../Subscription/FreeTrial'
import AppDownload from '../Subscription/AppDownload'
import Faq from '../Subscription/Faq'
import Pricing from '../Subscription/Pricing'
// import CustomerReviews from '../Common/CustomerReviews'
// import Blog from '../Common/Blog'
import FooterStyleFour from '../Layout/FooterStyleFour'

export default {
    name: 'Subscriptions',
    components: {
        Navbar,
        MainBanner,
        // Screenshots,
        Partner,
        IncludedBestFeatures,
        FreeTrial,
        AppDownload,
        Faq,
        // GettingBestApp,
        // Features,
        // Video,
        // IncludedBestFeatures,
        // AppScreens,
        SoftwareIntegrations,
        Pricing,
        // CustomerReviews,
        // Blog,
        FooterStyleFour,
    }
}
</script>