<template>
  <div class="nav-bar">
      <div class="left"><slot name="left"></slot></div>
      <div class="center"><slot name="center"></slot></div>
      <div class="right"><slot name="right"></slot></div>
  </div>
</template>

<script>
export default {
  components: {},
  props: {},
  data() {
    return {
    };
  }

}
</script>
<style scoped>
.nav-bar{
    width: 100%;
    height: 44px;
    display: flex;
    line-height: 44px;

}
.left, .right {
    width: 60px;
  }
  .center {
    flex: 1;
    text-align: center;
  }
</style>