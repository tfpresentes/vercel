<template>
  <div id="app">
    <TopBar msg="Cresça em volume"/>
    <Body msg="iShopee"/>
  </div>
</template>

<script>
import TopBar from './components/TopBar.vue'
import Body from './components/Body.vue'


export default {
  name: 'app',
  components: {
    TopBar,
    Body
  }
}
</script>

<style scoped>
body, html {
  height: 100%;
  width: 100%;
}
#app {
  background-image: linear-gradient(135deg,#eb4c00,#f2a900);
  height: 100%;
  width: 100%;
  margin: 0em;
}
</style>
