<template>
  <div id="app">
   
    <app-header></app-header>
    <!-- router -->
    <!--<router-view></router-view>-->
  <home></home>

    <!-- <app-list></app-list> -->
  </div>
</template>

<script>

// 引入Home组件
 import Home from './components/containers/Home/Home'
//  引入Header组件
  import AppHeader from './components/commons/Header/Header'

  // list
    // import AppList from './components/containers/List/List'
export default {
  name: 'App',
  // 注册组件
  components: {
   
     Home,AppHeader,
      // AppList
  }
}
</script>

<style>

</style>
