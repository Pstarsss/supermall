<template>
   <div class='maintabbar'>
     <tabbar>
       <tabbaritem>
         <span slot="tabitem-img" class="iconfont-ali">&#xe796;</span>
         <span slot="tabitem-title">首页</span>
       </tabbaritem>
       <tabbaritem>
         <span slot="tabitem-img" class="iconfont-ali">&#xe63c;</span>
         <span slot="tabitem-title">分类</span>
       </tabbaritem>
       <tabbaritem>
         <span slot="tabitem-img" class="iconfont-ali">&#xe796;</span>
         <span slot="tabitem-title">购物车</span>
       </tabbaritem>
       <tabbaritem>
         <span slot="tabitem-img" class="iconfont-ali">&#xe605;</span>
         <span slot="tabitem-title">我的</span>
       </tabbaritem>
     </tabbar>
   </div>
</template>

<script>
import tabbar from 'components/common/tabbar/tabbar.vue'
import tabbaritem from 'components/common/tabbar/tabitem.vue'
export default {
  components: {
    tabbar,
    tabbaritem
  },
  data() {
   return {
   };
},

}
</script>
<style lang='less' scoped>
</style>