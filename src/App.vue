<template>
  <v-app>
    <v-main>
      <HelloWorld />
    </v-main>
  </v-app>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";

export default {
  name: "App",

  components: {
    HelloWorld,
  },

  data: () => ({
    //
  }),
};
</script>
<style>
@font-face {
  font-family: "CaviarDreams";
  src: url("./assets/fonts/LouisGeorgeCafe.ttf") format("truetype");
}
</style>
