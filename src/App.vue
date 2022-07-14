<template>
  <Header></Header>
  <LeftSaidbar></LeftSaidbar>
  <Footer></Footer>
<!--  <img alt="Vue logo" src="./assets/logo.png">-->
<!--  <HelloWorld msg="Welcome to Your Vue.js App"/>-->
</template>

<script>
import Header from './components/layout/header.vue'
import Footer from './components/layout/footer.vue'
import LeftSaidbar from "./components/layout/left-saidbar.vue";

export default {
  name: 'App',
  components: {
    Header,
    Footer,
    LeftSaidbar
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
