<template>
  <div id="app">
    <div>
      <mainbar></mainbar>
      <router-view></router-view>
    </div>
  </div>
    
</template>
<script>
import mainbar from 'components/content/maintabbar/maintab.vue'

export default {
  name:'app',
  components:{
    mainbar
  }
}
</script>
<style>

@import "assets/css/base.css";

</style>
