<template>
    <div class="home-container_section home-container_section--top-long">
        <h2 class="u-text-centered">Yelp New York</h2>
        <div class="location-bar">
            <div class="tab-nav-container">
            <ul class="tab-nav js-tab-nav tab-nav--center js-tab-nav--center">
                <li v-for="(country,index) in countries" :key="index" class="tab-nav_item" role="presentation">
                    <router-link  class="tab-link tab-link--nav" :to="country.to" role="tab">
                        <span class="tab-link_label">{{ country.name }}</span>
                    </router-link>
                </li>
                <li class="tab-nav_item tab-nav_item--last" role="presentation">
                    <router-link  class="tab-link tab-link--nav" to="/locations" role="tab">
                        <span aria-hidden="true" style="width: 18px; height: 18px;" class="icon icon--18-search-small icon--size-18 icon--currentColor tab-link_icon js-tab-link_icon tab-link_icon-wrap">
                            <svg role="img" class="icon_svg">
                                <use xlink:href="#18x18_search_small"></use>
                            </svg>
                        </span>
                        <span class="tab-link_label">More Cities</span>
                    </router-link>
                </li>
            </ul>
        </div>
        </div>
        
    </div>
</template>

<script>
export default {
  name: "yelpactivitytopbar",
  components: {
  },
  data () {
    return {
        countries: [
            {
                "to": "/",
                "name": 'San Francisco'
            },
            {
                "to": "/",
                "name": 'San Jose'
            },
            {
                "to": "/",
                "name": 'Los Angeles'
            },
            {
                "to": "/",
                "name": 'Chicago'
            },
            {
                "to": "/",
                "name": 'Palo Alto'
            },
            {
                "to": "/",
                "name": 'Oakland'
            }
        ]
    }
  },
  methods: {
  }
};
</script>

<style lang="scss">

</style>