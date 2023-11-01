<script setup lang="ts">
import TestUnionProps from './components/TestUnionProps.vue';
</script>

<template>
  <div>
    <TestUnionProps :my-prop="'autocomplete'" />

    <TestUnionProps my-prop="is" />

    <TestUnionProps my-prop="" />
  </div>
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
