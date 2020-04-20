<template>
    <div class="home-container_section js-hot-new-businesses-section">
        <h3 class="explore-city_title">Hot &amp; New Businesses</h3>
        <div class="arrange arrange--wrap arrange--3-units arrange--30">
            <div class="arrange_unit" v-for="(product,index) in products" :key="index">
                <ProductCard :key="index" :product="product"></ProductCard>
            </div>
        </div>

        <div class="u-space-t2 u-text-centered">
            <a class="js-analytics-click explore-city_see-all" to="/search?attrs=NewBusiness">See more hot and new businesses</a>
        </div>

    </div>
</template>

<script>

import ProductCard from '@/components/Card/ProductCard'
import ProductList from '@/json/newbusiness.json'

export default {
  name: "newbusiness",
  components: {
      ProductCard
  },
  data () {
    return {
        products: ProductList
    }
  },
  methods: {
  }
};
</script>

<style lang="scss">

</style>