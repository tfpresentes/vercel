<template>
  <div id="app">
    <img alt="iShopee logo" src="./assets/logoIshopee.png">
    <HelloWorld msg="Cresça em volume"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'app',
  components: {
    HelloWorld
  }
}
</script>

<style>
#app {
  background-image: linear-gradient(to bottom, #EB4C00, #F2A900);
  padding-top: var(--header-height);
  transition: opacity .7s cubic-bezier(.4,0,.2,1);
  box-sizing: border-box;
  display: block;
  --home-max-width: 100vw;
  --gutter-width: 15px;
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
