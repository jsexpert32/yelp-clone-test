<template>
    <div class="homepage-hero_inner">
        <div class="u-text-centered">
            <h1 class="homepage-hero_logo" id="logo">
                <router-link to="/">Yelp</router-link>
            </h1>
        </div>
        <SearchBar></SearchBar>
        <Categories></Categories>
        <div class="u-text-centered homepage-hero_biz u-size-full business-link-hovercard--strong">                
            <span class="business-link-hovercard_business-link js-business-link"> 
                <router-link class="biz-name" to="/biz/cheshire-preston"><span>Cheshire</span></router-link>
            </span> 
        </div>
        <div class="u-text-centered homepage-hero_photo-owner u-size-full">
            <p>Photo by <router-link class="homepage-hero_photo-owner-link" to="/user_details?userid=RwthRRBnOLUoTPxfaQXn7A"><strong>Natalia K.</strong></router-link></p>
        </div>
    </div>
</template>

<script>

import SearchBar from '@/components/Form/SearchBar'
import Categories from '@/components/LandingPage/Categories'

export default {
  name: "LandingPageInner",
  components: {
      SearchBar,
      Categories
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