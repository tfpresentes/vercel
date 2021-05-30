<template>
  <div id="app">
    <TopBar msg="Cresça em volume"/>
    <div class="bg">
      <img src="./assets/bg.svg" alt="background image" class="background">
    </div>
  </div>
</template>

<script>
import TopBar from './components/TopBar.vue'

export default {
  name: 'app',
  components: {
    TopBar
  }
}
</script>

<style scoped>
body, html {
  height: 100%;
  width: 100%;
}
.bg {
  background-image: "./assets/bg.svg";
}
#app {
  background-image: linear-gradient(135deg,#eb4c00,#f2a900);
  height: 100%;
  width: 100%;
}
</style>
