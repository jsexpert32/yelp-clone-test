<template>
    <li class="list-island_item">
        <div class="media-block media-block--12">
            <div class="media-avatar">
                <a class="collection-card-container u-inline-block" href="/">
                    <div class="collection-card_photo-box u-inline-block" :style="getBackgroundImage(data.imagePath)">
                        <div class="collection-card_blur-overlay" :style="getBackgroundImage(data.imagePath)"></div>
                        <div class="collection-card_text-overlay u-flex u-flex-dead-center">
                            <span class="collection-item-count">
                                <span aria-hidden="true" style="width: 14px; height: 14px;" class="icon icon--14-save icon--size-14 icon--white icon--fallback-inverted">
                                    <svg role="img" class="icon_svg">
                                        <use xlink:href="#14x14_save"></use>
                                    </svg>
                                </span>
                            </span>
                        </div>
                    </div>
                </a>
            </div>
            <div class="media-story">
                <p class="list-island_item-title u-text-truncate media-title">
                    <a class="js-analytics-click" href="/" data-analytics-label="favorites link">
                        {{data.title}}
                    </a>
                </p>
                <p class="list-island_item-description">
                </p>
                <div class="list-island_item-owner">
                    <span>{{data.place_count}} Places</span>
                    <span> · </span> By
                    <a class="user-display-name js-analytics-click" href="/" 
                        >{{data.name}}</a>
                </div>
            </div>
        </div>
    </li>
</template>

<script>

export default {
  name: "collectioncard",
  props: ["data"],
  components: {
  },
  data () {
    return {
    }
  },
  methods: {
      getBackgroundImage(img_path) {
          let style= {}
          style['background-image'] = 'url(' + img_path +')'
          return style
      }
  }
};
</script>

<style lang="scss">

</style>