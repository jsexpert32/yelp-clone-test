<template>
    <div class="y-container">
        <div class="y-container_content">
            <div class="home-container home-container--first-top-short">
                <ActivityTopBar></ActivityTopBar>
                <NewBusiness></NewBusiness>
                <div class="home-container_section">
                    <div class="clearfix layout-block layout-a">
                        <LocalYelp> </LocalYelp>
                        <YelpEvent></YelpEvent>
                    </div>
                </div>
                <div class="home-container_section">
                    <div class="clearfix layout-block layout-a">
                        <ReviewOfDay></ReviewOfDay>
                        <RecentCollection></RecentCollection>
                    </div>
                </div>
                <RecentActivity></RecentActivity>
            </div>
        </div>
    </div>
</template>

<script>

import ActivityTopBar from './ActivityTopBar'
import NewBusiness from './NewBusiness'
import LocalYelp from './LocalYelp'
import YelpEvent from './YelpEvent'
import ReviewOfDay from './ReviewOfDay'
import RecentCollection from './RecentCollection'
import RecentActivity from './RecentActivity'

export default {
  name: "yelpactivity",
  components: {
      ActivityTopBar,
      NewBusiness,
      LocalYelp,
      YelpEvent,
      ReviewOfDay,
      RecentCollection,
      RecentActivity
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