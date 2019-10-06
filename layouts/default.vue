<template>
  <div class="relative">
    <Default-Header class="absolute inset-x-0 top-0" />
    <nuxt />
  </div>
</template>
<script>
import DefaultHeader from '@/components/DefaultHeader.vue'

export default{
  components:{
    DefaultHeader
  }
}
</script>
<style>

</style>
