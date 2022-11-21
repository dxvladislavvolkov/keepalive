<template>
  <div>data</div>
</template>

<script setup lang="ts">
import { onUnmounted, onMounted, ref } from 'vue'
const visible = ref(true);
onMounted(() => {
  console.log('mounted');
});
onUnmounted(() => {
  console.log('unmounted');
});
</script>
