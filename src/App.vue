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
  @import './main.css';
</style>