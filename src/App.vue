<template>
  <v-app>
    <v-main>
      <HelloWorld />
      <Home msg="Welcome to Your Vue.js App" />
    </v-main>
  </v-app>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
import Home from "./components/Home.vue";

export default {
  name: "App",

  components: {
    HelloWorld,
    Home,
  },

  data: () => ({
    //
  }),
};
</script>
<style>
@font-face {
  font-family: "CaviarDreams";
  src: local(../src/assets/fonts/LouisGeorgeCafe.ttf), url() format("truetype");
}
</style>
