<script>
import {store} from "./store.js";

import AppNav from "./components/AppNav.vue";
import AppMain from "./components/AppMain.vue"

export default{
  data(){
    return{
      store
    }
  },

  components:{
    AppNav,
    AppMain
  }
}

</script>

<template>
 
 <AppNav/>

 <AppMain/>



  
  
</template>

<style lang="scss">
@use "./newstyles/styles.scss" as *;




</style>
