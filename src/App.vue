<template>
  <img alt="SoftwareQC" src="./assets/logo.png" />
  <Home msg="SoftwareQC | A group of programmer in Quebec." />
</template>

<script>
import Home from "./components/Home.vue";
export default {
  name: "App",
  components: {
    Home: Home,
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
  margin-top: 40px;
}
</style>
