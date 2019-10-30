<template>
  <div id="app">
    <img width="25%" src="./assets/logo.png">
    <!-- <HelloWorld/> -->
        <RwvHeader />
    <router-view></router-view>
    <RwvFooter />
    <!-- <KBase/> -->
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld";
import KBase from  "./components/KBase";
import RwvHeader from "@/components/TheHeader";
import RwvFooter from "@/components/TheFooter";

export default {
  name: "App",
  components: {
    HelloWorld,
    KBase,
    RwvHeader,
    RwvFooter
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
