<!-- Footer.vue -->
<template>
    <div class="footer">
      <p>&copy; Wheels2Go. All rights reserved.</p>
    </div>
  </template>
  
<script>
  export default {
    name: "Footer",
  };
</script>
  
<style>
  .footer {
    background-image: linear-gradient(to right, #455a64, #90a4ae); /* Darker blue-grey to transparent */
    padding: 1rem;
    display: flex;
    align-items: center;
    justify-content: center;
    color: white;
  }
  
  p {
    margin: 0;
  }
</style>
  