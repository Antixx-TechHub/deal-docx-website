<template>
    <div>
        <Navbar class="navbar-style-two" />
        <PageHeader />
        <Stats />
        <Funfacts />
        <IAQSolutions />
        <FreeTrial />
        <FooterStyleFour />
    </div>
</template>

<script>
import Navbar from '../Layout/Navbar'
import PageHeader from '../CPQIntegration/PageHeader'
import IAQSolutions from '../CPQIntegration/IAQSolutions'
import Funfacts from '../CPQIntegration/Funfacts'
import Stats from '../CPQIntegration/Stats'
import FreeTrial from '../CPQIntegration/FreeTrial'
import FooterStyleFour from '../Layout/FooterStyleFour'

export default {
    name: 'CPQIntegration',
    components: {
        Navbar,
        PageHeader,
        IAQSolutions,
        Funfacts,
        Stats,
        FreeTrial,
        FooterStyleFour,
    }
}
</script>