<template>
  <div>
    <h1>Count: {{ count }}</h1>
    <button @click="count++">Increment</button>
  </div>
</template>

<script setup lang="ts">
let count = ref(0);
</script>
