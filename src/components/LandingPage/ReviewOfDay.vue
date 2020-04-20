<template>
    <div class="column column-alpha">
        <div class="js-rotd">
            <h3 class="boy_title">Review of the Day</h3>

            <div class="island island--light rotd">
                <div class="ypassport arrange arrange--12 u-space-b3">
                    <div class="arrange_unit">
                        <div class="photo-box pb-60s" data-hovercard-id="WphZWOuETu_51ZF4-2fiaQ">
                            <router-link to="/" class="js-analytics-click" data-analytics-label="user-photo">
                                <img alt="Sylvia H." class="photo-box-img" height="60" src="https://s3-media2.fl.yelpcdn.com/photo/yMEEPWkg6jiZ4D7e7C2RcA/60s.jpg"
                                    width="60">
                            </router-link>
                        </div>
                    </div>
                    <div class="arrange_unit arrange_unit--fill">
                        <strong>
                            <router-link class="user-display-name js-analytics-click" to="/" data-hovercard-id="WphZWOuETu_51ZF4-2fiaQ" data-analytics-label="about_me" id="dropdown_user-name">Sylvia H.</router-link>
                        </strong>
                        <ul class="user-passport-stats user-passport-stats--inline">
                            <li class="friend-count">
                                <span aria-hidden="true" style="fill: #f15c00; width: 18px; height: 18px;" class="icon icon--18-friends icon--size-18">
                                    <svg role="img" class="icon_svg">
                                        <use xlink:to="#18x18_friends"></use>
                                    </svg>
                                </span>
                                <b>265</b>
                            </li>
                            <li class="review-count">
                                <span aria-hidden="true" style="fill: #f15c00; width: 18px; height: 18px;" class="icon icon--18-review icon--size-18">
                                    <svg role="img" class="icon_svg">
                                        <use xlink:to="#18x18_review"></use>
                                    </svg>
                                </span>
                                <b>214</b>
                            </li>
                            <li class="is-elite responsive-small-display-inline-block">
                                <router-link to="/">Elite ’20</router-link>
                            </li>
                        </ul>

                        <div class="rotd_text">
                            Wrote a review for
                            <div class="business-link-hovercard js-business-link-hovercard business-link-hovercard--strong business-link-hovercard--inline">
                                <span class="business-link-hovercard_business-link js-business-link">
                                    <router-link class="biz-name js-analytics-click" data-analytics-label="biz-name" to="/biz/roma-antica-san-francisco-3"><span>Roma Antica</span></router-link>
                                </span>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="badge-banner badge-banner--blue">
                    Review of the Day
                    <img src="https://s3-media0.fl.yelpcdn.com/assets/public/40x40_rotd.yelp_styleguide.yji-8bb21835695e01eb298b00f01db91d20.png"
                        width="40" class="badge-banner_img" role="presentation">
                </div>


                <div class="u-space-t3 u-space-b3">
                    <div class="biz-rating biz-rating-large clearfix">
                        <div>
                            <div class="i-stars i-stars--regular-5 rating-large" title="5.0 star rating">
                                <img class="offscreen" height="303" src="https://s3-media0.fl.yelpcdn.com/assets/public/stars.yelp_design_web.yji-9b34e39ccbeb1c01a8e5ce9462ff64c1.png"
                                    width="84" alt="5.0 star rating">
                            </div>
                        </div>
                        <span class="rating-qualifier">
                            8/28/2019
                        </span>
                    </div>
                </div>
                <p class="rotd_comment-text">
                    I came here with a party of 3 on a regular weekday at 6:30PM. We were seated immediately, but the restaurant started to get
                    packed shortly. APPEARANCE &amp; SEATING: I love how the front of the restaurant is an open window/wall,
                    so the restaurant doesn't get too stuffy. The interior of the restaurant is simple and brown with log
                    tables. Behind the bar area, there is a brick wall with an opening window showing the wooden ...
                    <router-link to="/" class="rotd_read-more js-analytics-click" data-analytics-label="read more">Continue reading</router-link>
                </p>
            </div>

            <p class="u-text-centered">
                <router-link class="boy_more-link js-analytics-click" to="/" data-analytics-label="archive">Read previous reviews</router-link>
            </p>
        </div>

    </div>
</template>

<script>



export default {
  name: "yelpevent",
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