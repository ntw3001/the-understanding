<script setup lang="ts">
  import Hello from './components/hellow_Orld.vue';
  import myComponent from './components/myComponent.vue';
  import globalStyle from './components/globalStyle.vue';
  import localStyle from './components/localStyle.vue';

  const message = 'Hello World';

  function calculate(x: number, y: number): number {
    return x + y;
  }
</script>

<template>
  <Hello/>
  <h1>Looka me I'm a {{message}}</h1>
  <div>A number is {{ 4 * 4 }}</div>
  <div>A calculation is {{ calculate(5, 6) }}</div>
  <myComponent/>
  <globalStyle/>
  <localStyle/>
</template>

<style scoped>

</style>
