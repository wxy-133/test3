<template>
  <div id="app">
    <router-view></router-view>
    <MainTarBar></MainTarBar>
  </div>
</template>

<script>
import MainTarBar from './components/content/mainTarbar/MainTarBar'
export default {
  name: 'App',
  components:{
   MainTarBar
  }
}
</script>
<style scoped>

  .tar-bar-item{
    flex: 1;
    text-align: center;
  }
</style>
