<template>
  <div id="app">
    <Billboards />
  </div>
</template>

<script>
import Billboards from "./components/Billboards.vue";

export default {
  name: "app",
  components: {
    Billboards
  }
};
</script>

<style lang="scss">
body {
  margin: 0;
  padding: 0;
}

#app {
  font-family: "Roboto Condensed", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #545454;
}
</style>
