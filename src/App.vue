<template>
  <div id="app">
    <Navigation />
    <Lander />
    <Card />
  </div>
</template>

<script>
import Navigation from "./components/includes/nav.vue"; //import the component
import Lander from "./components/Lander.vue";
import Card from "./components/card.vue";
export default {
  name: "App",
  components: {
    Navigation, //instantiate it here
    Lander,
    Card,
  },
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
