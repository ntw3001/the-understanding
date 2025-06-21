<script setup lang="ts">
  const mySite = 'https://www.example.com';
</script>

<template>
  <div>
    <h1>Welcome to My Site</h1>
    <p>Visit us at: <a :href="mySite" target="_blank">{{ mySite }}</a></p>
  </div>
</template>

<style scoped>
  h1 {
    color: #42b983;
  }

  p {
    font-size: 16px;
  }

  a {
    color: #42b983;
    text-decoration: none;
  }

  a:hover {
    text-decoration: underline;
  }
</style>
