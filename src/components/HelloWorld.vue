<script setup lang="ts">
defineProps({
  msg: { type: String, default: '' },
});
</script>

<template>
  <h1>{{ msg }}</h1>
</template>

<style scoped></style>
