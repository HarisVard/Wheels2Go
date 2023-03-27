<!-- AppBar.vue -->
<template>
    <div class="app-bar">
      <h1>Wheel2Go</h1>
      <!-- Add your menu or other elements here -->
    </div>
  </template>
  
<script>
  export default {
    name: "AppBar",
  };
</script>
  
<style>
  .app-bar {
    background-image: linear-gradient(to right, #455a64, #90a4ae); /* Darker blue-grey to transparent */
    padding: 1rem;
    display: flex;
    align-items: center;
    justify-content: space-between;
    color: white;
  }
  
  h1 {
    margin: 0;
    font-size: 1.5rem;
  }
</style>
  