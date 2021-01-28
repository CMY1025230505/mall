<template>
  <div id="app">
    <h2>hahaha</h2>
    <router-view />
  </div>
</template>

<script>
import Home from 'views/Home'

export default {
  name: "app",
  components: {
    Home
  },
};
</script>

<style>
@import "`assets/style/base.css";
</style>
