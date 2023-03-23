<template>
  <div>
    <the-header title="RememberMe"></the-header>
    <the-tab-bar></the-tab-bar>
  </div>
</template>

<script>
import TheHeader from "./components/layouts/TheHeader.vue";
import TheTabBar from "./components/learning-resources/TheTabBar.vue";

export default {
  components: {
    TheHeader,
    TheTabBar,
  },
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap");

* {
  box-sizing: border-box;
}

html {
  font-family: "Roboto", sans-serif;
}

body {
  margin: 0;
}
</style>
