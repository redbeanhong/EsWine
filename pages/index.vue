<template lang="pug">
  #index
    h1 hello
    Navbar
    Banner
    Product
    Footbar
</template>
<style lang="scss">
h1 {
  @apply text-5xl;
}
h2 {
  @apply text-3xl;
}
</style>
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
