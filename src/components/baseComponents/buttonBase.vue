<script setup lang="ts">
defineProps<{
  msg: string
}>()
</script>

<template>
  <button>{{ msg }}</button>
</template>

<style scoped>
button {
  width: 20%;
  height: auto;
  background-color: rgb(105, 105, 255);
  font-size: 25px;
}
</style>
