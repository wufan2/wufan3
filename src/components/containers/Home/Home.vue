<template>
  <div class="home">
    <app-banner></app-banner>
    <app-rew></app-rew>
    <app-goods></app-goods>
    <app-goodl></app-goodl>
    <app-goodbox></app-goodbox>
    <app-goodboxl></app-goodboxl>
  
     
    
   
  </div>
</template>

<script>
// 引入banner
import AppBanner from './Banner'
// 引入rew
import AppRew from './Rew'
// 
import AppGoods from './goods'
// 
import AppGoodl from './goodl'

import AppGoodbox from './goodbox'

import AppGoodboxl from './goodboxl'

export default {
  name: "home",
  // 注册banner
  components: {
    AppBanner,AppRew,
 AppGoods,AppGoodl,
    AppGoodbox,AppGoodboxl,
    
   
  }
};
</script>
<style lang="scss">
  .home {
    padding-top:56px;
  }
</style>


