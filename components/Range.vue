<template>
  <div class="ring rounded ring-green-400 w-40">
    <URange v-model="value" name="range" />
  </div>
</template>

<script setup>
const value = ref(5);
</script>
