<!-- AppBar.vue -->
<template>
    <div class="app-bar">
      <h1>Your App Name</h1>
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
    background-color: #607d8b; /* Blue-grey */
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
  