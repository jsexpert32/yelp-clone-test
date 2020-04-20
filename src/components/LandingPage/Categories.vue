<template>
  <ul class="homepage-hero_categories js-header-nav text-centered">
        <li class="homepage-hero_category" data-analytics-label="plumbers">
            <div>
                <span aria-hidden="true" style="width: 24px; height: 24px;" class="icon icon--24-plumbers icon--size-24 icon--inverse icon--fallback-inverted">
                    <svg role="img" class="icon_svg">
                        <use xlink:href="#24x24_plumbers"></use>
                    </svg>
                </span>
                <router-link class="homepage-hero_link" to="/search?cflt=Plumbing&amp;find_loc=San+Francisco%2C+CA">Plumbers</router-link>
            </div>
        </li>
        <li class="homepage-hero_category" data-analytics-label="restaurants">
            <div>
                <span aria-hidden="true" style="width: 18px; height: 18px;" class="icon icon--18-food icon--size-18 icon--inverse icon--fallback-inverted">
                    <svg role="img" class="icon_svg">
                        <use xlink:href="#18x18_food"></use>
                    </svg>
                </span>
                    <router-link class="homepage-hero_link" to="/search?cflt=restaurants&amp;find_loc=San+Francisco%2C+CA">Restaurants</router-link>
            </div>
        </li>
        <li class="homepage-hero_category" data-analytics-label="home services" data-component-bound="true">
            <div>
                <span aria-hidden="true" style="width: 18px; height: 18px;" class="icon icon--18-home-services icon--size-18 icon--inverse icon--fallback-inverted">
                    <svg role="img" class="icon_svg">
                        <use xlink:href="#18x18_home_services"></use>
                    </svg>
                </span>
                <a class="homepage-hero_link">Home Services</a>
                    <span aria-hidden="true" style="width: 14px; height: 14px;" class="icon icon--14-triangle-down icon--size-14 icon--inverse icon--fallback-inverted u-triangle-direction-down dropdown_arrow">
                        <svg role="img" class="icon_svg">
                            <use xlink:href="#14x14_triangle_down"></use>
                        </svg>
                    </span>
            </div>
        </li>
        <li class="homepage-hero_category" data-analytics-label="delivery">
            <div>
                <span aria-hidden="true" style="width: 18px; height: 18px;" class="icon icon--18-delivery icon--size-18 icon--inverse icon--fallback-inverted">
                    <svg role="img" class="icon_svg">
                        <use xlink:href="#18x18_delivery"></use>
                    </svg>
                </span>
                <router-link class="homepage-hero_link" to="/search?find_desc=Delivery&amp;find_loc=San+Francisco%2C+CA">Delivery</router-link>
            </div>
        </li>
    </ul>
</template>

<script>
export default {
  name: "categories",
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
    .homepage-hero_categories {
        .icon {
            margin-right:3px;
        }
    }
</style>
