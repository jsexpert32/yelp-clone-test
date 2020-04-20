<template>
    <div class="card business-passport-card">
        <div class="card_photo">
            <div class="photo-box photo-box--interactive photo-box--background" :style="getBackgroundImage(product.imagePath)">
                <a href="/biz/le-sia-new-york-4" class="photo-box_link js-analytics-click" data-analytics-label="biz-photo">
                    <img class="photo-box-img" height="400" :src="product.imagePath"
                         width="600">
                </a>
            </div>
        </div>
        <div class="card_body">
            <div class="card_content">
                <h3 class="card_content-title--linked u-text-truncate">

                    <div class="business-link-hovercard js-business-link-hovercard">
                        <span class="business-link-hovercard_business-link js-business-link">

        <a class="biz-name js-analytics-click"  href="/"><span>{{product.title}}</span></a>
                        </span>
                    </div>

                </h3>
                <div class="biz-rating biz-rating-large clearfix">




                    <div class="i-stars i-stars--regular-5 rating-large" title="5.0 star rating">
                        <img class="offscreen" height="303" src="https://s3-media0.fl.yelpcdn.com/assets/public/stars.yelp_design_web.yji-9b34e39ccbeb1c01a8e5ce9462ff64c1.png"
                            width="84" alt="5.0 star rating">
                    </div>


                    <span class="review-count rating-qualifier">
                            {{product.review_count}} reviews
                    </span>

                </div>

                <div class="price-category">
                    <span v-if="product.price_range" class="bullet-after"> 
                        <span  class="business-attribute price-range">{{product.price_range}}</span>
                    </span>
                    <span class="category-str-list">
                        {{product.category_name}}
                    </span>


                </div>

                <div class="neighborhood u-text-truncate u-space-t1 u-space-b1">
                    <span class="neighborhood-str-list">
                        {{product.address}}
                    </span>

                </div>
                <p class="business-passport-card_date-opened">
                    <span aria-hidden="true" style="width: 18px; height: 18px;" class="icon icon--18-flame icon--size-18 icon--currentColor">
                        <svg role="img" class="icon_svg">
                            <use xlink:href="#18x18_flame"></use>
                        </svg>
                    </span> {{product.start_date}}
                </p>
            </div>
        </div>
    </div>
</template>

<script>


export default {
  name: "productcard",
  props: ["product"],
  components: {
  },
  data () {
    return {
    }
  },
  methods: {
      getBackgroundImage(imgPath) {
          let style = {}
          style['background-image'] = 'url(' + imgPath + ')'
          return style
      }
  }
};
</script>

<style lang="scss">

</style>