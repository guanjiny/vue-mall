<template>
  <tab-bar>
    <tab-bar-item path="/">
      <img slot="item-icon-active" src="~assets/img/tabbar/home-active.svg" alt="">
      <img slot="item-icon" src="~assets/img/tabbar/home.svg" alt="">
      <div slot="item-text">首页</div>
    </tab-bar-item>
    <tab-bar-item path="/category">
      <img slot="item-icon-active" src="~assets/img/tabbar/category-active.svg" alt="">
      <img slot="item-icon" src="~assets/img/tabbar/category.svg" alt="">
      <div slot="item-text">分类</div>
    </tab-bar-item>
    <tab-bar-item path="/shopcart">
      <img slot="item-icon-active" src="~assets/img/tabbar/shopcart-active.svg" alt="">
      <img slot="item-icon" src="~assets/img/tabbar/shopcart.svg" alt="">
      <div slot="item-text">购物车</div>
    </tab-bar-item>
    <tab-bar-item path="/profile">
      <img slot="item-icon-active" src="~assets/img/tabbar/profile-active.svg" alt="">
      <img slot="item-icon" src="~assets/img/tabbar/profile.svg" alt="">
      <div slot="item-text">我的</div>
    </tab-bar-item>
  </tab-bar>
</template>

<script>
  import TabBar from "components/common/tabbar/TabBar";
  import TabBarItem from "components/common/tabbar/TabBarItem";
  export default {
    name: "MainTabBar",
    components: {
      TabBar,
      TabBarItem
    }
  }
</script>

<style scoped>

</style>
