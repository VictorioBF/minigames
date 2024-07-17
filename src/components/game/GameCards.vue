<script setup lang="ts">
defineProps<{
  solved: boolean
}>()
</script>

<template>
  <div v-if="solved" class="card">assim</div>
  <div v-else class="card">assado</div>
</template>

<style scoped></style>
