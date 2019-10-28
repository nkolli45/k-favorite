<template>
  <div id="app">
    <img width="25%" src="./assets/logo.png">
    <HelloWorld/>
    <KBase/>
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld";
import KBase from  "./components/KBase";

export default {
  name: "App",
  components: {
    HelloWorld,
    KBase
  }
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
