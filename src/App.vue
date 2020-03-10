<template>
  <div>
    <router-view></router-view>
    <tab-bar-main></tab-bar-main>
  </div>
</template>
<script>
  import TabBarMain from "components/content/mainTabBar/TabBarMain";
  export default{
    name:'app',
    components:{
        TabBarMain
    }
  }
</script>
<style>
    @import "assets/css/base.css";
</style>
