<script setup lang="ts">
  const mySite = 'https://www.example.com';
  const imgWidth = 400;
  const imgInfo = {
    alt: "IANA Logo",
    src: "https://www.iana.org/_img/2025.01/iana-logo-header.svg"
  };

</script>

<template>
  <div>
    <h1>Welcome to My Site</h1>
    <p>Visit us at: <a :href="mySite" target="_blank">{{ mySite }}</a></p>
    <img v-bind:="imgInfo" :width="imgWidth" /> // we can bind an object full of sttributes qwith v-bind or just throw the : in front to bind a specific constant
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
