<template>
  <img alt="Vue logo" src="./assets/kotakode.png" style="width: 20%" />
  <!-- <HelloWorld msg="Welcome to Your Vue.js App" /> -->
  <LoginPage />
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import LoginPage from "./components/LoginPage.vue";

export default {
  name: "App",
  components: {
    // HelloWorld
    LoginPage,
  },
};
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
