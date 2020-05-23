<template>
  <TarBar>
      <TarBarItem path="/home">
          <img slot="item-icon" src="../../../assets/img/tabbar/home.png">
          <img slot="item-icon-active" src="../../../assets/img/tabbar/home_active.png">
          <div slot="item-text">首页</div>
      </TarBarItem>
      <TarBarItem path="/category">
          <img slot="item-icon" src="../../../assets/img/tabbar/category.png">
          <img slot="item-icon-active" src="../../../assets/img/tabbar/category_active.png">
          <div slot="item-text">精选</div>
      </TarBarItem>
      <TarBarItem path="/cart">
          <img slot="item-icon" src="../../../assets/img/tabbar/shopcart.png">
          <img slot="item-icon-active" src="../../../assets/img/tabbar/shopcart_active.png">
          <div slot="item-text">购物车</div>
      </TarBarItem>
      <TarBarItem path="/profile">
          <img slot="item-icon" src="../../../assets/img/tabbar/profile.png">
          <img slot="item-icon-active" src="../../../assets/img/tabbar/profile_active.png">
          <div slot="item-text">我的</div>
      </TarBarItem>

  </TarBar>
</template>

<script>
  import TarBar from '../tarbar/Tarbar'
  import TarBarItem from '../tarbar/TarBarItem'
export default {

  components: {
      TarBar,
      TarBarItem
  },
  data() {
    return {
    };
  }
}
</script>
<style scoped>

</style>