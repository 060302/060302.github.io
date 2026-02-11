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
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
