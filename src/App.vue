<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <Home msg="Welcome to Your Vue.js App" />
</template>

<script>
import Home from "./components/Home.vue";

export default {
  name: "App",
  components: {
    Home,
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

@font-face{
  font-family: "CaviarDreams";
  src: local("CaviarDreams"),
  url(../src/assets/Louis George Cafe.ttf) format("truetype");
}

</style>
