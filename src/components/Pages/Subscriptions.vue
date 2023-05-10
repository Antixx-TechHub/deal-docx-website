<template>
        <div>
            <Navbar class="navbar-style-two" />
            <MainBanner />
            <!-- <Screenshots /> -->
            <!-- <Partner /> -->
            <!-- <SoftwareIntegrations /> -->
            <!-- <IncludedBestFeatures /> -->
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
    import MainBanner from '../HomePage/MainBanner'
    // import Screenshots from '../HomePage/Screenshots'
    import Partner from '../HomePage/Partner'
//     import IncludedBestFeatures from '../HomePage/IncludedBestFeatures'
    // import GettingBestApp from '../HomePage/GettingBestApp'
    // import Features from '../HomePage/Features'
    // import Video from '../Common/Video'
    // import IncludedBestFeatures from '../HomePage/IncludedBestFeatures'
    // import AppScreens from '../HomePage/AppScreens'
//     import SoftwareIntegrations from '../HomePage/SoftwareIntegrations'
    import FreeTrial from '../HomePage/FreeTrial'
    import AppDownload from '../HomePage/AppDownload'
//     import Faq from '../HomePage/Faq'
    import Pricing from '../HomePage/Pricing'
    // import CustomerReviews from '../Common/CustomerReviews'
    // import Blog from '../Common/Blog'
    import FooterStyleFour from '../Layout/FooterStyleFour'
    
    export default {
        name: 'HomePageThree',
        components: {
            Navbar,
            MainBanner,
            // Screenshots,
        //     Partner,
        //     IncludedBestFeatures,
            FreeTrial,
            AppDownload,
        //     Faq,
            // GettingBestApp,
            // Features,
            // Video,
            // IncludedBestFeatures,
            // AppScreens,
        //     SoftwareIntegrations,
            Pricing,
            // CustomerReviews,
            // Blog,
            FooterStyleFour,
        }
    }
    </script>