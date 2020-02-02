<template>
  <div id="app">
<<<<<<< HEAD
    
    <router-view/>
=======
    <keep-alive exclude="Detail">
      <router-view></router-view>
    </keep-alive>
    <main-tab-bar></main-tab-bar>
    <icon></icon>
    <svg-icon></svg-icon>
>>>>>>> d875067e72014d52a395d551186ca10edc79a98d
  </div>
</template>

<script>
<<<<<<< HEAD
  export default {
    name: 'App',
    components:{

=======
  import MainTabBar from 'content/mainTabbar/MainTabBar'
  import Icon from 'content/Icon/Icon.vue'
  import SvgIcon from 'content/Icon/svg.vue'

  export default {
    name: 'app',
    components: {
      MainTabBar,
      Icon,
      SvgIcon
>>>>>>> d875067e72014d52a395d551186ca10edc79a98d
    }
  }
</script>

<style>
<<<<<<< HEAD
  @import "/asset/css/base.css";
=======
  @import "assets/css/base.css";

  #app {
    position: relative;
  }
>>>>>>> d875067e72014d52a395d551186ca10edc79a98d
</style>
