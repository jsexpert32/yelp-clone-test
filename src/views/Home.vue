<template>
  <div>
    <LandingPageContainer></LandingPageContainer>
    <BestBusiness></BestBusiness>
    <YelpActivity></YelpActivity>
    <BrowserCategory></BrowserCategory>
    <MobileApps></MobileApps>
    <Footer></Footer>
  </div>
</template>

<script>
import LandingPageContainer from '@/components/LandingPage/LandingPageContainer'
import BestBusiness from '@/components/LandingPage/BestBusiness'
import BrowserCategory from '@/components/LandingPage/BrowserCategory'
import MobileApps from '@/components/LandingPage/MobileApps'
import Footer from '@/components/LandingPage/Footer'
import YelpActivity from '@/components/LandingPage/YelpActivity'

export default {
  name: "home",
  components: {
    LandingPageContainer,
    BestBusiness,
    BrowserCategory,
    YelpActivity,
    MobileApps,
    Footer
  },
  data () {
    return {
    }
  },
  methods: {
  }
};
</script>

<style lang="scss">
</style>
