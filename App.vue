<template>
  <div id="app">
    <HomeComponent />
  </div>
</template>

<script>
import HomeComponent from "@/views/HomeComponent.vue";

export default {
  name: 'App',
  components: {
    HomeComponent
  }
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
