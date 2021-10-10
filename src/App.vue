<template>
 <div class=''>
   <Header/>
   <div class='flex  '>
   <Sidebar/>
   
     <Display />
   </div>
   
 </div>
  <router-view/>
</template>
<script>
import Header from './components/Header.vue'
import Sidebar from './components/Sidebar.vue';
import Display from './components/Display.vue'

export default {
    name: 'App',
    components:{
      Header,
      Sidebar,
        Display
    },

}
</script>

