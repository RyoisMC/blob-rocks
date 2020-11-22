<template>
  <div id="app">
    <particles />
  </div>
</template>

<script>
import particles from "./components/particles.vue";

export default {
  name: "App",
  components: {
    particles,
  },
};
</script>

<style>
body,
html {
  margin: 0;
  height: 100%;
  overflow: hidden;
}
#app {
  background-image: url("/blobbanner.jpg");
  height: 100%;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}
</style>