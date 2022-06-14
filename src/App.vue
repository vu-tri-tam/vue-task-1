<script setup>
import Header from './component/homeComponent/headerComponent/header.vue';
import IndexHome from './component/homeComponent/indexHome.vue';


</script>

<template>
 <div id="app">
   <IndexHome/>
 </div>

</template>
<script>
export default {
  data(){
    return {
        mess : 'SASS/SCSS loader'
    }
  }
}
</script>
<style lang="scss" scoped>
// $backGround: black;
body{
    margin: 0!important;
    padding: 0!important;
    box-sizing: border-box;
}
  #app{
    // background-color: $backGround;

  }
</style>

