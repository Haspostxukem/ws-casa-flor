<template>
  <MenuTop></MenuTop>
</template>

<script>
import MenuTop from "./components/MenuTop.vue";
export default {
  name: "App",
  components: {
    MenuTop,
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
}
body {
  margin: 0;
}

div {
  display: flex;
}
</style>
