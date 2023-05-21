<script>
import AppHeader from "./components/AppHeader.vue";
import AppProject from "./components/AppProject.vue";
import AppFooter from "./components/AppFooter.vue";
export default {
  components: {
    AppHeader,
    AppProject,
    AppFooter,
  },
};
</script>

<template>
  <AppHeader />
  <AppProject />
  <AppFooter />
</template>

<style lang="scss">
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: "Press Start 2P", cursive;
  font-family: "Roboto", sans-serif;
}
</style>
