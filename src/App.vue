<template>
  <div id="app">
    <Header msg="Cresça em volume"/>
    <Body msg="iShopee"/>
    <Footer msg="ERP"/>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Body from './components/Body.vue'
import Footer from './components/Footer.vue'


export default {
  name: 'app',
  components: {
    Header,
    Body,
    Footer
  }
}
</script>

<style>
body, html {
  height: 100%;
  width: 100%;
}
#app {
  width: 100%;
  margin: 0;
}
@font-face {
  font-family: "Now";
  src: local("Now"),
   url(/src/fonts/Now/NOW-BLACK.otf) format("truetype");
}
</style>
