<script>
import StockList from "./components/StockList.vue";

export default {
  name: "App",
  components: {
    StockList,
  },
};
</script>

<template>
  <div class="container">
    <StockList />
  </div>
</template>

<style scoped>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
