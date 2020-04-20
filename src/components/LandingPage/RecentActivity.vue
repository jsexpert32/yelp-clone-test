<template>
    <div class="home-container_section home-container_section--top-long">
        <h2 class="activity-feed_title u-text-centered">Recent Activity</h2>
        <div class="js-activity-feed u-space-t4" data-feed-type="nearby" data-component-bound="true">
            <div class="arrange arrange--wrap arrange--3-units arrange--30">
                <div class="arrange_unit js-column-a">
                    <ActivityCard v-for="(item,index) in aList" :key="index"></ActivityCard>
                </div>
                <div class="arrange_unit js-column-b">
                    <ActivityCard v-for="(item,index) in bList" :key="index"></ActivityCard>
                </div>
                <div class="arrange_unit js-column-c">
                    <ActivityCard v-for="(item,index) in cList" :key="index"></ActivityCard>
                </div>
                
            </div>
            <p class="js-load-more activity-feed_load-more">
                    <router-link class="js-analytics-click" to="/">
                        <span aria-hidden="true" style="width: 24px; height: 24px;" class="icon icon--24-chevron-down icon--size-24 icon--currentColor u-space-r-half">
                            <svg role="img" class="icon_svg">
                                <use xlink:href="#24x24_chevron_down"></use>
                            </svg>
                        </span>
                        <span class="js-load-more-text">Show more activity in San Francisco</span>
                    </router-link>
                </p>
        </div>
    </div>
</template>

<script>

import ActivityCard from '@/components/Card/ActivityCard'

export default {
  name: "recentactivity",
  components: {
      ActivityCard
  },
  data () {
    return {
        aList: [1,2,3],
        bList: [4,5,6],
        cList: [7,8,9]
    }
  },
  methods: {
  }
};
</script>

<style lang="scss">

</style>