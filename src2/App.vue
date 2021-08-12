<template>
  <div>
    <router-view/>
    <FooterGuide v-show="$route.meta.showFooter"/>
  </div>
</template>

<script>
  // console.log($route.meta.showFooter)
import FooterGuide from './components/FooterGuide/FooterGuide.vue'
export default {
  components:{
    FooterGuide
  },
}

</script>

<style lang="stylus" rel ="stylesheet/stylus">
  .app
    color:red
</style>