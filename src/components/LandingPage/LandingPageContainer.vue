<template>
  <div class="y-container homepage-hero" :style="getBAckgroundImage()">
      <div class="y-container_content">
          <div class="hero-header js-main-header">
              <div class="arrange arrange--18">
                  <div class="arrange_unit arrange_unit--fill">
                      <div class="hero-header_nav hero-header_nav--main nowrap">
                          <ul class="header-nav">
                              <li id="write-review" class="header-nav_item js-analytics-click" data-analytics-label="write-review">
                                <router-link to="/writeareview" class="header-nav_link">
                                    Write a Review
                                </router-link>
                              </li>
                              <li id="events" class="header-nav_item js-analytics-click" data-analytics-label="events">
                                <router-link to="/events" class="header-nav_link">
                                    Events
                                </router-link>
                              </li>
                              <li id="talk" class="header-nav_item js-analytics-click" data-analytics-label="talk">
                                <router-link to="/talk" class="header-nav_link">
                                    Talk
                                </router-link>
                              </li>
                          </ul>
                      </div>
                  </div>
                  <div class="arrange_unit nowrap">
                        <ul class="header-nav hero-header_nav main-header_account">
                            <li class="header-nav_item u-space-r2" id="header-log-in">
                                <router-link to="/login" class="header-nav_link header-nav_link--log-in js-analytics-click">
                                    Log In
                                </router-link>
                            </li>
                            <li class="header-nav_item u-space-r0 js-analytics-click" id="header-sign-up">
                                <router-link to="/signup" class="ybtn ybtn--primary header-nav_button nowrap">Sign Up</router-link>
                            </li>
                        </ul>
                    </div>
              </div>
          </div>
          <LandingPageInner></LandingPageInner>
      </div>
  </div>
</template>

<script>

import LandingPageInner from './LandingPageInner'


export default {
  name: "LandingPageContainer",
  components: {
      LandingPageInner
  },
  data () {
    return {
      backgroundImg: 'url(https://s3-media2.fl.yelpcdn.com/assets/srv0/yelp_large_assets/eea3522f4348/assets/img/home/hero_photos/BWRT755ImlKnGpjV4udRdQ.jpg)'
    }
  },
  methods: {
    getBAckgroundImage() {
      let style = {}
      style['background-image'] = this.backgroundImg
      return style
    }
  }
};
</script>

<style lang="scss">
</style>
