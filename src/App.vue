<script>
import {store} from "./store.js";

import AppNav from "./components/AppNav.vue";
import AppMain from "./components/AppMain.vue"
import AppFooter from './components/AppFooter.vue';

export default{
  data(){
    return{
      store,
      recentpost:["Aneman loros adermus","Caritatem coribus diptus","Carpen nostrum caritas","Ribeluss ad interim","Nullun crimen sina lege","Par in parem imperium non abet"],
      tags:["D&G","boots","Brown","Casual","Fabric","Flowers","grey","hat","Hipster","Lines","multipurpose","lines","New York","Outdoors","red","summer","sweater","travel","warm","white","winter"]
    }
  },

  components:{
    AppNav,
    AppMain,
    AppFooter
  },
  
}

</script>

<template>
 
 <AppNav/>

 <AppMain/>

 <AppFooter :post="recentpost" :footerTag="tags"/>





  
  
</template>

<style lang="scss">
@use "./newstyles/styles.scss" as *;




</style>
