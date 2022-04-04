<template lang="pug">
  .continer.flex.flex-wrap
    ProductCard(v-for="(item,index) in 8" :key="index" class="w-1/4")
</template>
<script>
import ProductCard from '@/components/ProductCard.vue'
export default {
  components: {
    ProductCard
  }
}
</script>
