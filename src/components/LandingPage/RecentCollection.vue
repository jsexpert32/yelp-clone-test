<template>
  <div class="column column-beta js-explore-city_event-section">
      <div class="js-recent-collections">
          <h3 class="boy_title">
            Recent Collections
        </h3>
        <div class="island recent-collections island--light list-island">
            <div class="arrange arrange--30 arrange--equal">
                <div class="arrange_unit">
                    <ul class="list-island_set">
                        <CollectionCard v-for="(item,index) in collectionList" :key="index" :data="item"></CollectionCard>
                    </ul>
                </div>
            </div>
        </div>
        <p class="u-text-centered">
            <a class="boy_more-link js-analytics-click" href="/">
                Browse more collections
            </a>
        </p>
      </div>
  </div>
</template>

<script>

import CollectionCard from '@/components/Card/CollectionCard'
import CollectionList from '@/json/recentCollection.json'

export default {
  name: "RecentCollections",
  components: {
      CollectionCard
  },
  data () {
    return {
        collectionList: CollectionList
    }
  },
  methods: {
  }
};
</script>

<style lang="scss">
</style>
