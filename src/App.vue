<template>
  <div id="app">
    <router-view />
    <mainTabBar />
  </div>
</template>

<script>
import MainTabBar from "@/components/content/mainTabBar/mainTabBar";

export default {
  name: "App",
  components: {
    MainTabBar
  }
};
</script>

<style>
@import "assets/css/base.css";
</style>
