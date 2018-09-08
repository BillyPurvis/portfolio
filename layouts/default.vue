<template>
  <div class="wrapper">
    <Brand/>
    <nuxt/>
    <my-footer/>
  </div>
</template>

<script>
import MyFooter from '~/components/Footer.vue'
import Brand from '~/components/Brand.vue'

export default {
  components: {
    MyFooter,
    Brand
  }
}
</script>

<style lang="scss">
.wrapper {
  max-width: 990px;
  margin: 0 auto;
} 
</style>
