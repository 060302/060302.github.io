<script setup lang="ts">
import { ref } from 'vue'

const message = ref<string>('Hello Vue.js!')
</script>

<template>
  <div id="app">
    <p>{{ message }}</p>
  </div>
</template>

<style scoped>
p {
  font-size: 1.5rem;
  color: inherit;
}
</style>
