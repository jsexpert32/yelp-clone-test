<template>
  <form @submit.prevent="search()" class="business-search-form main-search yform u-space-b0 js-business-search-form" role="search">
    <div class="arrange arrange--equal arrange--stack-small">
      <div class="arrange_unit" v-click-outside="loseSuggestionFocus">
        <div class="main-search_suggestions-field search-field-container find-decorator">
          <label class="pseudo-input business-search-form_input business-search-form_input--find" for="find_desc">
                        <div class="pseudo-input_wrapper">
                            <span class="pseudo-input_text business-search-form_input-text">Find</span>
                            <span class="pseudo-input_field-holder">
                                <input v-model="searchWord" autocomplete="off" maxlength="64" @focus="suggestionFocused()" placeholder="burgers, barbers, spas, handymen…" value="" class="pseudo-input_field business-search-form_input-field">
                            </span>
                        </div>
                    </label>
          <div v-show="isSuggestionFocused" class="main-search_suggestions suggestions-list-container search-suggestions-list-container">
            <SuggestionList></SuggestionList>
          </div>
        </div>
      </div>

      <div class="arrange_unit">
        <div class="arrange">
          <div class="arrange_unit arrange_unit--fill">
            <div class="main-search_suggestions-field search-field-container near-decorator">
              <label class="pseudo-input business-search-form_input business-search-form_input--near">
                                <div class="pseudo-input_wrapper">
                                <span class="pseudo-input_text business-search-form_input-text">Near</span>
                                    <span class="pseudo-input_field-holder">
                                        <input autocomplete="off" id="dropperText_Mast" maxlength="80" name="find_loc" placeholder="address, neighborhood, city, state or zip" value="San Francisco, CA" class="pseudo-input_field business-search-form_input-field" aria-autocomplete="list" tabindex="2">
                                        <input type="hidden" name="ns" value="1">
                                    </span>
                                </div>
                            </label>
              <div class="main-search_suggestions suggestions-list-container location-suggestions-list-container hidden">
                <ul class="suggestions-list" role="listbox" aria-label="Search results"></ul>
              </div>
            </div>
          </div>
          <div class="arrange_unit">
            <button class="ybtn ybtn--primary ybtn--small business-search-form_button" id="header-search-submit" tabindex="3" title="Search"
              type="submit" value="submit">
                            <span class="main-search_action-icon-wrap js-search-icon-wrap">
                                <span v-show="!searching" aria-hidden="true" style="width: 24px; height: 24px;" class="icon icon--24-search icon--size-24 icon--currentColor">
                                    <svg role="img" class="icon_svg">
                                        <use xlink:href="#24x24_search">
                                           </use>
                                    </svg>
                                </span>
                                <span class="u-offscreen">Search</span>
                            </span>
                            <Spinner v-show="searching"></Spinner>
                            </button>
          </div>
        </div>
      </div>
    </div>
  </form>
</template>

<script>
import SuggestionList from '../LandingPage/SuggestionList'
import Spinner from '../Common/Spinner'
import ClickOutside from 'vue-click-outside'


export default {
  name: "SearchBar",
  components: {
    SuggestionList,
    Spinner
  },
  data () {
    return {
      isSuggestionFocused: false,
      searching: false,
      searchWord: ""
    }
  },
  directives: {
    ClickOutside
  },
  methods: {
    suggestionFocused() {
      this.isSuggestionFocused = true
    },
    loseSuggestionFocus() {
      this.isSuggestionFocused = false
    },
    search() {
      let self = this
      this.searching = true
      setTimeout(function() {
        self.$router.push("/search?find_desc=" + self.searchWord + "&find_loc=San+Francisco%2C+CA&ns=1")
      },2000)
    }
  }
};
</script>