<script setup lang="ts">
import { ref } from 'vue'

const count = ref(0)
</script>

<template>
  <div>
    <h1>WebDIY</h1>
    <p class="muted">Vue 3 + TypeScript + Vite</p>
    <div class="card">
      <button type="button" @click="count++">count is {{ count }}</button>
    </div>
  </div>
</template>

<style scoped>
.muted {
  margin: 0.5rem 0 1.5rem;
  color: #888;
}
</style>
