<template>
  <div id="app">
    <TopNavigation />
  </div>
</template>

<script>
import TopNavigation from "@/components/TopNavigation.vue";
export default {
  name: "App",
  components: {
    TopNavigation,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
