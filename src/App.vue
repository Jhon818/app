<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" />
    <Title />
    <Hero />
  </div>
</template>

<script>
import Title from "./components/title.vue";
import Hero from "./components/hero.vue";
export default {
  name: "App",
  components: {
    Title,
    Hero,
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
