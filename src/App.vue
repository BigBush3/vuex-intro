<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <Component1 />
</template>

<script>
import Component1 from "./components/Component1";

export default {
  components: { Component1 },
  name: "App",
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
