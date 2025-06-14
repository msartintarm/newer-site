<script setup>
import { ref } from 'vue'

defineProps({
  msg: String,
})

const count = ref(0)
</script>

<template>
  <h1>{{ msg }}</h1>
  <div class="card">
    <button type="button" @click="count++">count is {{ count }}</button>
  </div>
 <p class="footer">Copyright 2025. All rights reserved.</p>
</template>

<style scoped>
.footer {
  color: #888;
}
</style>
