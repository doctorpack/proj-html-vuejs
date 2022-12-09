<template>
  <div id="app">
    <MyHeader :navbarOptions="navbarOptions"/>
    <MyMain/>
    <MyFooter :footerNavbarOptions="footerNavbarOptions" :onlineOrder="onlineOrder" :generalInfo="generalInfo" :openingHours="openingHours"/>
  </div>
</template>

<script>
import MyHeader from "./components/MyHeader.vue"
import MyMain from "./components/MyMain.vue"
import MyFooter from "./components/MyFooter.vue"

export default {
  name: 'App',
  components: {
    MyHeader,
    MyMain,
    MyFooter
  },
  data(){
    return{
      navbarOptions:['<span class="highlighted"> Home </span>', "meet the band" ,  "Live dates", "Latest news",  "Albums",  'Fans'],
      footerNavbarOptions:['<span class="highlighted">Home</span>', "meet the band", "Live dates", "Latest news", "Albums", 'Fans'],
     
    }
  }
}
</script>

<style lang="scss">
  @import "./assets/scss/common.scss";
</style>
