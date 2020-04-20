<template>
    <div class="column column-beta js-explore-city_event-section">
        <h3 class="explore-city_title">Official Yelp Event</h3>
        <div class="card">
            <div class="card_photo">

                <div class="photo-box photo-box--interactive photo-box--background" style="background-image: url(https://s3-media1.fl.yelpcdn.com/ephoto/aIT5-SpMjzE641t1ojr-CQ/300s.jpg)">
                    <router-link to="/" class="photo-box_link js-analytics-click"
                        data-analytics-label="biz-photo">
                        <img alt="Yelp's Meet Your Maker Cocktail Club: Featuring Erin Hines" class="photo-box-img" height="300" src="https://s3-media1.fl.yelpcdn.com/ephoto/aIT5-SpMjzE641t1ojr-CQ/300s.jpg"
                            srcset="https://s3-media1.fl.yelpcdn.com/ephoto/aIT5-SpMjzE641t1ojr-CQ/348s.jpg 1.16x" width="300">
                    </router-link>
                </div>
            </div>
            <div class="card_content">
                <h3 class="card_content-title--linked u-text-truncate">
                    <router-link class="explore-city_event-link js-analytics-click" to="/">Yelp's Meet Your Maker Cocktail Club: Featuring Erin Hines</router-link>
                </h3>
                <p class="card_content-text event-card_description" itemprop="description">
                    Join us for an evening of Valentine's Day-inspired cocktails and spirited stories with Erin Elizabeth Hines (Guesthouse Restaurant,
                    and owner of Bitter Girl Bitters) and Jeff Burkhart, award-winning bartender and Marin IJ columnist,
                    at Hanson of Sonoma's Tasting Room in Sausalito. Erin will mix up a few of her favorite cocktails made
                    with Hanson of Sonoma Vodka &amp; Whiskey and her homemade bitters. All libations will be paired with
                    some mouthwatering "love bites". In between drinks, Jeff will lead a fun audience Q &amp; A where guests
                    can ask everything they've always wanted to know about cocktails and bartenders but were afraid to ask.
                    Admission is $10. This gets you: 3 cocktails, light bites, drink recipes, and a Yelp shot glass. Anyone
                    with a Yelp account who is over the age of 21 can RSVP. * Space is limited to just 50 guests. +1s are
                    allowed. ****************** HOW TO RSVP ****************** STEP 1: Click the red RSVP button on this
                    page STEP 2: Wait to receive an email confirmation several days before the event, and that will be your
                    indication you're on the guest list!
                </p>
                <p class="u-text-truncate u-text-subtle event-card_date">
                    Thu, Feb 6, 6:30 pm
                    <span class="event-card_end-time">- 8:00 pm</span>
                </p>
            </div>
        </div>
        <div class="u-space-t2 u-text-centered">
            <router-link to="/" class="explore-city_see-all js-analytics-click" data-analytics-label="link-more">See all events</router-link>
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