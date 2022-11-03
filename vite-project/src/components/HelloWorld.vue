<script setup>
defineProps({
  msg: String
})
</script>

<template>
  <h1>{{ msg }}</h1>
</template>

<style scoped>
  h1{
    background-color: #CCC;
    padding: 20px;
    border-radius: 20px;
  }
</style>
