<script setup lang="ts">
defineProps<{
  msg: string
}>()
</script>

<template>
  <div id="tools">toolbartoolbartoolbartoolbartoolbartoolbartoolbar</div>
  <div id="gameContainer">
    <div class="gameRow"></div>
    <div class="gameRow"></div>
    <div class="gameRow"></div>
    <div class="gameRow"></div>
  </div>
</template>

<style scoped>
#tools {
  padding: 0.5rem 1rem;
  margin-bottom: 0.5rem;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  border: 1px rgba(255, 255, 255, 0.1) solid;
  border-radius: 0.5rem;
}
#gameContainer {
  padding: 0;
  display: flex;
  flex-direction: column;
  outline: 1px blue solid;
}
</style>
