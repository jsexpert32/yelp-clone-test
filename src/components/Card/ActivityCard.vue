<template>
    <div class="island island--light activity-feed_item activity-feed_item--review js-item-type-review activity-feed_item--first-load">
        <div class="feed-item_header">
            <div class="arrange arrange--12">
                <div class="arrange_unit">
                    <div class="photo-box pb-30s">
                        <a href="/" class="js-analytics-click" data-analytics-label="user-photo">
                            <img class="photo-box-img" height="30" src="https://s3-media2.fl.yelpcdn.com/photo/PTWI40-vmOOEmhW5TsfQFg/30s.jpg" srcset="https://s3-media2.fl.yelpcdn.com/photo/PTWI40-vmOOEmhW5TsfQFg/ss.jpg 1.33x,https://s3-media2.fl.yelpcdn.com/photo/PTWI40-vmOOEmhW5TsfQFg/60s.jpg 2.00x,https://s3-media2.fl.yelpcdn.com/photo/PTWI40-vmOOEmhW5TsfQFg/90s.jpg 3.00x"
                                width="30">
                        </a>
                    </div>
                </div>
                <div class="arrange_unit arrange_unit--fill">
                    <a class="feed-item_user-link js-analytics-click" href="/" data-analytics-label="user-name">
                        <strong>Kevin D.</strong>
                    </a>
                    <br>
                    <span class="feed-item_action">Wrote a review</span>
                </div>

                <div class="arrange_unit"></div>
            </div>
        </div>
        <div class="feed-item_scrollable-content js-scrollable-content">
            <div class="feed-item_hero">

                <div class="photo-box photo-box--interactive photo-box--background" style="background-image: url(https://s3-media2.fl.yelpcdn.com/bphoto/HzzieakIhDGV_NZzKyRmAw/l.jpg)">
                    <a href="/biz/chase-center-san-francisco-2" class="photo-box_link js-analytics-click" data-analytics-label="biz-photo">
                        <img class="photo-box-img" height="400" src="https://s3-media2.fl.yelpcdn.com/bphoto/HzzieakIhDGV_NZzKyRmAw/l.jpg" srcset="https://s3-media2.fl.yelpcdn.com/bphoto/HzzieakIhDGV_NZzKyRmAw/o.jpg 1.67x"
                            width="600">

                    </a>
                </div>
            </div>
            <div class="feed-item_body">

                <div class="feed-item_title u-space-b2 u-text-truncate feed-item_title--bordered">

                    <div class="business-link-hovercard js-business-link-hovercard business-link-hovercard--strong">
                        <span class="business-link-hovercard_business-link js-business-link">
            <a class="biz-name js-analytics-click" data-analytics-label="biz-name" href="/biz/chase-center-san-francisco-2"><span>Chase Center</span></a>
                        </span>

                    </div>

                </div>


                <div class="u-space-b2">

                    <div class="i-stars i-stars--regular-4 rating-large" title="4.0 star rating">
                        <img class="offscreen" height="303" src="https://s3-media0.fl.yelpcdn.com/assets/public/stars.yelp_design_web.yji-9b34e39ccbeb1c01a8e5ce9462ff64c1.png"
                            width="84" alt="4.0 star rating">
                    </div>

                </div>

                <p class="feed-item_review-content u-break-word">
                    <span class="js-truncated-comment">
                Went to a Warriors game and had an amazing time! The arena is super modern and aesthetic on the inside. Lots of food options too. We had crab fries from Sams Chowder and some dessert baos from Paper L...
                <a href="javascript:;" class="u-nowrap continue-reading js-load-full-review js-analytics-click" data-analytics-label="continue-reading">Continue reading</a>
            </span>

                    <span class="js-full-comment u-hidden">Went to a Warriors game and had an amazing time! The arena is super modern and aesthetic on the inside. Lots of food options too. We had crab fries from Sams Chowder and some dessert baos from Paper Lanterns. Something to note, they had a promotion for Chase card users where you get $5 off a food purchase of $30!</span>
                </p>

            </div>
        </div>
        <div class="feed-item_footer">
            <div class="arrange arrange--12">
                <div class="arrange_unit arrange_unit--fill">
                    <div class="js-deanon-modal-container">
                        <div class="js-deanon-modal u-hidden">
                            <div class="modal_body">
                                <div class="u-text-centered u-space-t6 u-space-b6">
                                    <h3 class="u-space-b3">Others will see how you vote!</h3>

                                    <div class="u-space-b3">
                                        <img src="https://s3-media0.fl.yelpcdn.com/assets/public/200x120_ufc_globe.yelp_deanonymize_ufc.yji-f871a0ff7872e619c872b58091e967a2.png">
                                    </div>

                                    <div class="u-space-b2" style="width:76%;margin:auto;">
                                        Heads up: From now on, other Yelpers will be able to see how you voted. Want to chime in?
                                    </div>
                                    <form action="/review_feedback/deanonymize/1.0.0" class="js-deanon-form" method="POST">
                                        <input type="hidden" name="csrftok" class="csrftok" value="25021cffb18d97c2d9e55ad2c3f3771ffe264957d3eaeb051efc5a0423779dc9">

                                        <button href="javascript:;" type="submit" value="submit" class="ybtn ybtn--primary ybtn--small js-let-me-vote-button u-space-b1"><span>Yes, Let Me Vote!</span></button>
                                    </form>
                                    <div class="js-maybe-later-button u-pseudo-link">
                                        <small>Maybe Later</small>
                                    </div>
                                </div>
                            </div>
                        </div>

                    </div>

                    <ul class="ufc-actions">
                        <li class="ufc-action">
                            <a href="/login" class="ufc-action_link js-ufc-action_link ufc-action_link--useful js-analytics-click" data-analytics-label="ufc"
                                data-has-voted="0" data-icon-color="#f15c00" data-name="useful" data-review-id="mBbmugdN31_RtrJlXXxKkw">
                                <span class="show-tooltip">
                        <span aria-hidden="true" style="width: 24px; height: 24px;" class="icon icon--24-useful-outline icon--size-24 icon--ufc js-icon--ufc">
    <svg role="img" class="icon_svg">
        <use xlink:href="#24x24_useful_outline"></use>
    </svg>
</span>
                                <span class="tooltip-wrapper">
                            <span class="tooltip">Useful</span>
                                </span>
                                </span>

                                <span class="ufc-action_count js-ufc-action_count">
                        
                    </span>
                            </a>
                        </li>
                        <li class="ufc-action">
                            <a href="/login" class="ufc-action_link js-ufc-action_link ufc-action_link--funny js-analytics-click" data-analytics-label="ufc"
                                data-has-voted="0" data-icon-color="#41a700" data-name="funny" data-review-id="mBbmugdN31_RtrJlXXxKkw">
                                <span class="show-tooltip">
                        <span aria-hidden="true" style="width: 24px; height: 24px;" class="icon icon--24-funny-outline icon--size-24 icon--ufc js-icon--ufc">
    <svg role="img" class="icon_svg">
        <use xlink:href="#24x24_funny_outline"></use>
    </svg>
</span>
                                <span class="tooltip-wrapper">
                            <span class="tooltip">Funny</span>
                                </span>
                                </span>

                                <span class="ufc-action_count js-ufc-action_count">
                        
                    </span>
                            </a>
                        </li>
                        <li class="ufc-action">
                            <a href="/login" class="ufc-action_link js-ufc-action_link ufc-action_link--cool js-analytics-click" data-analytics-label="ufc"
                                data-has-voted="0" data-icon-color="#0097ec" data-name="cool" data-review-id="mBbmugdN31_RtrJlXXxKkw">
                                <span class="show-tooltip">
                        <span aria-hidden="true" style="width: 24px; height: 24px;" class="icon icon--24-cool-outline icon--size-24 icon--ufc js-icon--ufc">
    <svg role="img" class="icon_svg">
        <use xlink:href="#24x24_cool_outline"></use>
    </svg>
</span>
                                <span class="tooltip-wrapper">
                            <span class="tooltip">Cool</span>
                                </span>
                                </span>

                                <span class="ufc-action_count js-ufc-action_count">
                        
                    </span>
                            </a>
                        </li>
                    </ul>

                </div>
                <div class="arrange_unit">
                    <div class="arrange">
                        <div class="arrange_unit compliment-success-msg js-compliment-success-msg u-hidden">
                            <span>Sent</span>
                        </div>
                        <div class="arrange_unit">
                            <a href="/login" class="compliment-btn js-compliment-btn compliment-btn--not-sent feed-item_action-link feed-item_action-link--compliment js-analytics-click"
                                data-analytics-label="compliment">
                                <span class="show-tooltip">
                    <span aria-hidden="true" style="width: 24px; height: 24px;" class="icon icon--24-compliment icon--size-24 icon--currentColor icon--compliment">
    <svg role="img" class="icon_svg">
        <use xlink:href="#24x24_compliment"></use>
    </svg>
</span>
                                <span class="tooltip-wrapper">
                        <span class="tooltip">Send a Compliment</span>
                                </span>
                                </span>
                            </a>
                        </div>
                    </div>

                </div>
            </div>

            <div class="u-hidden popin js-popin popin--compliment">
                <div class="popin_close js-popin_close">×</div>
                <div class="section-header">
                    <p><strong>Send Compliment</strong></p>
                </div>



                <form class="compliment-form js-compliment-form yform yform--continuous u-space-b0" method="POST">
                    <input type="hidden" name="csrftok" class="csrftok" value="c3a1d134b18e4556f2c143dac49f723e1a3cf38d7df9319afb269afa912d0363">
                    <div class="compliment-form_types">
                        <fieldset>
                            <label class="radio-check">
        <input checked="checked" name="compliment_type" type="radio" value="plain">
        <div class="compliment-icon compliment-icon--plain">
            <span aria-hidden="true" style="width: 18px; height: 18px;" class="icon icon--18-compliment icon--size-18 icon--white icon--fallback-inverted u-sticky-top">
    <svg role="img" class="icon_svg">
        <use xlink:href="#18x18_compliment"></use>
    </svg>
</span>
        </div>
        <span>Thank You</span>
    </label>

                            <label class="radio-check">
        <input name="compliment_type" type="radio" value="writer">
        <div class="compliment-icon compliment-icon--writer">
            <span aria-hidden="true" style="width: 18px; height: 18px;" class="icon icon--18-pencil icon--size-18 icon--white icon--fallback-inverted u-sticky-top">
    <svg role="img" class="icon_svg">
        <use xlink:href="#18x18_pencil"></use>
    </svg>
</span>
        </div>
        <span>Good Writer</span>
    </label>

                            <label class="radio-check">
        <input name="compliment_type" type="radio" value="note">
        <div class="compliment-icon compliment-icon--note">
            <span aria-hidden="true" style="width: 18px; height: 18px;" class="icon icon--18-file icon--size-18 icon--white icon--fallback-inverted u-sticky-top">
    <svg role="img" class="icon_svg">
        <use xlink:href="#18x18_file"></use>
    </svg>
</span>
        </div>
        <span>Just a Note</span>
    </label>

                            <label class="radio-check">
        <input name="compliment_type" type="radio" value="more">
        <div class="compliment-icon compliment-icon--more">
            <span aria-hidden="true" style="width: 18px; height: 18px;" class="icon icon--18-write-more icon--size-18 icon--white icon--fallback-inverted u-sticky-top">
    <svg role="img" class="icon_svg">
        <use xlink:href="#18x18_write_more"></use>
    </svg>
</span>
        </div>
        <span>Write More</span>
    </label>

                            <label class="radio-check">
        <input name="compliment_type" type="radio" value="photos">
        <div class="compliment-icon compliment-icon--photos">
            <span aria-hidden="true" style="width: 18px; height: 18px;" class="icon icon--18-camera icon--size-18 icon--white icon--fallback-inverted u-sticky-top">
    <svg role="img" class="icon_svg">
        <use xlink:href="#18x18_camera"></use>
    </svg>
</span>
        </div>
        <span>Great Photo</span>
    </label>

                            <label class="radio-check">
        <input name="compliment_type" type="radio" value="funny">
        <div class="compliment-icon compliment-icon--funny">
            <span aria-hidden="true" style="width: 18px; height: 18px;" class="icon icon--18-funny icon--size-18 icon--white icon--fallback-inverted u-sticky-top">
    <svg role="img" class="icon_svg">
        <use xlink:href="#18x18_funny"></use>
    </svg>
</span>
        </div>
        <span>You're Funny</span>
    </label>

                            <label class="radio-check">
        <input name="compliment_type" type="radio" value="cute">
        <div class="compliment-icon compliment-icon--cute">
            <span aria-hidden="true" style="width: 18px; height: 18px;" class="icon icon--18-heart icon--size-18 icon--white icon--fallback-inverted u-sticky-top">
    <svg role="img" class="icon_svg">
        <use xlink:href="#18x18_heart"></use>
    </svg>
</span>
        </div>
        <span>Cute Pic</span>
    </label>

                            <label class="radio-check">
        <input name="compliment_type" type="radio" value="hot">
        <div class="compliment-icon compliment-icon--hot">
            <span aria-hidden="true" style="width: 18px; height: 18px;" class="icon icon--18-flame icon--size-18 icon--white icon--fallback-inverted u-sticky-top">
    <svg role="img" class="icon_svg">
        <use xlink:href="#18x18_flame"></use>
    </svg>
</span>
        </div>
        <span>Hot Stuff</span>
    </label>

                            <label class="radio-check">
        <input name="compliment_type" type="radio" value="profile">
        <div class="compliment-icon compliment-icon--profile">
            <span aria-hidden="true" style="width: 18px; height: 18px;" class="icon icon--18-profile icon--size-18 icon--white icon--fallback-inverted u-sticky-top">
    <svg role="img" class="icon_svg">
        <use xlink:href="#18x18_profile"></use>
    </svg>
</span>
        </div>
        <span>Like Your Profile</span>
    </label>

                            <label class="radio-check">
        <input name="compliment_type" type="radio" value="cool">
        <div class="compliment-icon compliment-icon--cool">
            <span aria-hidden="true" style="width: 18px; height: 18px;" class="icon icon--18-cool icon--size-18 icon--white icon--fallback-inverted u-sticky-top">
    <svg role="img" class="icon_svg">
        <use xlink:href="#18x18_cool"></use>
    </svg>
</span>
        </div>
        <span>You're Cool</span>
    </label>

                            <label class="radio-check">
        <input name="compliment_type" type="radio" value="list">
        <div class="compliment-icon compliment-icon--list">
            <span aria-hidden="true" style="width: 18px; height: 18px;" class="icon icon--18-list icon--size-18 icon--white icon--fallback-inverted u-sticky-top">
    <svg role="img" class="icon_svg">
        <use xlink:href="#18x18_list"></use>
    </svg>
</span>
        </div>
        <span>Great Lists</span>
    </label>

                        </fieldset>
                    </div>
                    <input type="hidden" name="dst_user_id" value="GP7coYb7DrF0fKPajndM0g">
                    <input type="hidden" name="review_id" value="mBbmugdN31_RtrJlXXxKkw">
                    <div class="arrange u-space-t2">
                        <div class="arrange_unit arrange_unit--fill">
                            <input name="message" type="text" placeholder="Message" class="js-compliment-form_message">
                        </div>
                        <div class="arrange_unit">

                            <button class="ybtn ybtn--primary ybtn--small compliment-form_send-button js-analytics-click" data-analytics-label="compliment-send"
                                title="Send" type="submit" value="submit">
                    <span class="js-compliment-form_send-button_text">Send</span>
                        
    </button>
                        </div>
                    </div>
                    <div data-default-error-msg="Hmm, something didn't work out there." class="js-compliment-form_error-msg u-hidden text-error u-space-t1"></div>
                </form>

            </div>
        </div>
    </div>
</template>

<script>

export default {
  name: "activitycard",
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