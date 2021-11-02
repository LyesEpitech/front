<template>
  <div id="app">
    <ComponentPreview /> 
  </div>
</template>

<script>
import ComponentPreview from "./components/ComponentPreview.vue"
export default {
  name: "App",
  components: {
    ComponentPreview,
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
