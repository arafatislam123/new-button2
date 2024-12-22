<script setup>
const color='yellow'
</script>

<template>
  <button class="text-white font-bold py-2 px-4 rounded" :class="[
    `bg-${color}-500`,
    `hover:bg-${color}-700`,
  ]">
    Button

  </button>

</template>

<style scoped>

</style>
