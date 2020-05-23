<template>
   <div id="home" class="wrapper">
      <NavBar class="nav-bar"><div slot="center">购物街</div></NavBar>
   </div>
</template>

<script>
  // 导入的文件按空格区分清楚，方便查找
 import NavBar from '../../components/common/navbar/NavBar'

  export default {
    name: "Home",
    data() {
      return {
        
      }
    },
    components: {
      NavBar
    
    },
    created() {
      
    },
     mounted() {
       
     },

  }
</script>

<style scoped>
.nav-bar{
  width: 100%;
  height: 44px;
  background-color: pink;
  color: white;
}
</style>