<template lang="pug">
  #index
    Navbar
    Banner
    Product
    Footbar
</template>

<script>
import Navbar from '@/components/Navbar.vue'
import Banner from '@/components/Banner.vue'
import Product from '@/components/Product.vue'
import Footbar from '@/components/Footbar.vue'
export default {
  components: {
    Navbar,
    Banner,
    Product,
    Footbar
  }
}
</script>
