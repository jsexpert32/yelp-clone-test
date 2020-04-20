<template>
    <ul class="suggestions-list">
        <li v-for="(item,index) in items" :key="index" class="item suggestion suggestions-list-item " @click.prevent="goToSearch(item,$event)" role="option" tabindex="0" aria-label="category">
            <div class="media-block">
                <div aria-hidden="true" class="media-avatar"><span class="icon icon--24-food icon--size-24" aria-hidden="true" style="width: 24px; height: 24px;"><svg class="icon_svg"><use :xlink:href="item.icon_link"></use></svg></span></div>
                <div class="media-story"><span class="suggestion-detail"><span class="suggestion-detail suggestion-title suggestion-name">{{item.name}}</span></span>
                    <small class="suggestion-detail suggestion-subtitle suggestion-location"></small>
                </div>
            </div>
        </li>
    </ul>
</template>

<script>


export default {
  name: "suggestionlist",
  components: {
  },
  data () {
    return {
        items: [
            {
                "name": "Restaurants",
                "icon_link": "#24x24_food"
            },
            {
                "name": "Bars",
                "icon_link": "#24x24_nightlife" 
            },
            {
                "name": "Delivery",
                "icon_link": "#24x24_order" 
            },
            {
                "name": "Takeout",
                "icon_link": "#24x24_shopping" 
            },
            {
                "name": "Reservations",
                "icon_link": "#24x24_reservation" 
            },
            {
                "name": "Waitlist",
                "icon_link": "#24x24_stopwatch" 
            }
        ]
    }
  },
  methods: {
      goToSearch(item,evt) {
          evt.stopPropagation()
          this.$router.push("/search?find_desc=" + item.name + "&find_loc=San+Francisco%2C+CA&ns=1")
      }
  }
};
</script>

<style lang="scss">
.suggestions-list-item:hover {
    background: #0073bb!important;
}
</style>