<template>
  <div class="y-container u-bg-color-alt">
      <div class="y-container_content">
          <div class="home-container home-container--first-top-short home-container--last-bottom-short">
              <div class="section__a5c5a__Dl_UN">
                  <h2 class="u-space-b4__a5c5a__1sQ5m u-text-centered__a5c5a__B6qeJ">Browse Businesses by Category</h2>
                  <div class="u-space-b5__a5c5a__2_noh u-text-centered__a5c5a__B6qeJ">
                      <div class="lemon--div__a5c5a__1mboc arrange__a5c5a__UHqhV gutter-30__a5c5a__2PiuS layout-equal__a5c5a__2jcUj border-color--default__a5c5a__2oFDT">
                          <div v-for="(item,index) in list1" :key="index" class="lemon--div__a5c5a__1mboc arrange-unit__a5c5a__1piwO border-color--default__a5c5a__2oFDT">
                            <router-link class="category-tile__a5c5a__16LEC island__a5c5a__1pU7x island--light__a5c5a__33s4t js-browse-businesses_category_tile js-browse-businesses_category"  :to="item.link">
                                <img class="tile-image__a5c5a__2UKf4 u-space-b1__a5c5a__3kBMH" width="72" :src="item.imgPath">
                                <h3 class="title__a5c5a__2hApb u-text-truncate__a5c5a__Gq9_5 h4__a5c5a__8yeJ1">{{item.label}}</h3>
                            </router-link>
                        </div>
                      </div>
                  </div>
                  <div class="u-text-centered__a5c5a__B6qeJ">
                      <div class="lemon--div__a5c5a__1mboc arrange__a5c5a__UHqhV gutter-30__a5c5a__2PiuS layout-equal__a5c5a__2jcUj border-color--default__a5c5a__2oFDT">
                          <div v-for="(item,index) in list2" :key="index" class="lemon--div__a5c5a__1mboc arrange-unit__a5c5a__1piwO border-color--default__a5c5a__2oFDT">
                            <router-link class="category-tile__a5c5a__16LEC island__a5c5a__1pU7x island--light__a5c5a__33s4t js-browse-businesses_category_tile js-browse-businesses_category"  :to="item.link">
                                <img class="tile-image__a5c5a__2UKf4 u-space-b1__a5c5a__3kBMH" width="72" :src="item.imgPath">
                                <h3 class="title__a5c5a__2hApb u-text-truncate__a5c5a__Gq9_5 h4__a5c5a__8yeJ1">{{item.label}}</h3>
                            </router-link>
                        </div>
                      </div>
                  </div>
              </div>
          </div>
      </div>
  </div>
</template>

<script>

import data from '@/json/browserCategory.json'

export default {
  name: "browsercategories",
  components: {
  },
  data () {
    return {
        list1: data.list1,
        list2: data.list2
    }
  },
  methods: {
  }
};
</script>

<style lang="scss">
</style>
