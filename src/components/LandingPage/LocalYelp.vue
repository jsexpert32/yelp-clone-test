<template>
    <div class="column column-alpha js-explore-city_weekly-section">
        <h3 class="explore-city_title">The Local Yelp</h3>
        <div class="card u-full-width">
            <div class="card_photo">
                <div class="photo-box photo-box--interactive photo-box--background" style="background-image: url(https://s3-media4.fl.yelpcdn.com/wphoto/RrlAflY8LlDinWIVUJOFtw/h.jpg)">
                    <router-link to="/" class="photo-box_link js-analytics-click" data-analytics-label="biz-photo">
                        <img alt="The Boombox Studio" class="photo-box-img" height="250" src="https://s3-media4.fl.yelpcdn.com/wphoto/RrlAflY8LlDinWIVUJOFtw/h.jpg"
                            width="600">
                    </router-link>
                </div>
            </div>
            <div class="card_content">
                <h3 class="u-text-truncate card_content-title--linked">
                    <router-link class="explore-city_weekly-link js-analytics-click"  to="/">New year, new fitness resolution?</router-link>
                </h3>
                <p class="card_content-text">It’s that time of year again—everyone’s looking to get fit for the new year. But what if you just want to
                    enjoy getting fit? You can do that, and more, at these hot spots. (Literally, they’re hot—because exercise.)
                    Don’t throw in the towel either… you’re definitely going to need it later.</p>
                <p class="u-text-subtle">The Local Yelp</p>
            </div>
        </div>

        <div class="u-space-t2 u-text-centered">
            <router-link to="/" class="explore-city_see-all js-analytics-click" >See more</router-link>
        </div>

    </div>
</template>

<script>

export default {
  name: "localyelp",
  components: {
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