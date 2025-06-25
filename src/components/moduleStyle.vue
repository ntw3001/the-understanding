<template>
  <h1 v-bind:class="MikeLasses['m-class']">mobular-css-with-dollar-money-syntax.-It's-kebab-case!</h1>
  <p :class="MikeLasses.nClass">sameWithCamelCase!youDeclareTheClassALittleDifferently!</p>

</template>

<style module="MikeLasses">
  .m-class {
    background: olive;
    color: firebrick;
  }

  .nClass {
    color: blue;
    font-weight: lighter;
  }

</style>
