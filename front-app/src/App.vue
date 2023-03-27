<template>
  <div id="app">
    <app-bar></app-bar>

    <main>
      <router-view></router-view>
    </main>

    <Footer></Footer>
  </div>
</template>

<script>
import AppBar from "./components/AppBar.vue";
import Footer from "./components/Footer.vue";

export default {
  name: "App",
  components: {
    AppBar,
    Footer,
  },
};
</script>

<style>
/* Add any global CSS styles for your app layout here */
#app {
  display: flex;
  flex-direction: column;
  min-height: 100vh; /* Set the minimum height to the full viewport height */
}

main {
  flex-grow: 1; /* Allow the main content to grow and push the footer to the bottom */
}
</style>
