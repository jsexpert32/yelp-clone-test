<template>
  <div class="wrap">
      <SearchViewTopBar></SearchViewTopBar>
      <Footer></Footer>
  </div>
</template>

<script>

import SearchViewTopBar from '@/components/Common/SearchViewTopBar'
import Footer from '@/components/LandingPage/Footer'

export default {
  name: "SearchView",
  components: {
      SearchViewTopBar,
      Footer
  },
  data () {
    return {
    }
  },
  methods: {
  }
};
</script>
