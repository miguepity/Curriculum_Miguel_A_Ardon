<template>
  <div id="app">
    <router-view></router-view>
  </div>
</template>

<script>
import Cv from './components/Cv.vue'

export default {
  name: 'app',
  components: {
    Cv
  },
  mounted(){
   $(".button-collapse").sideNav();
 }
}
</script>
