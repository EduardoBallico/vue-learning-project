<template>
  <button @click="increment">Count is: {{ count }}</button>
</template>

<script setup>
  import { ref, onMounted } from 'vue'

  const count = ref(0)

  function increment() {
    count.value++
  }

  onMounted(() => {
    console.log(`The initial count is ${count.value}.`)
  })
</script>

<style scoped>
  button {
    background-color: #41b883;
    border: none;
    border-radius: 0.25rem;
    color: #fff;
    font-size: 1.25rem;
    padding: 0.5rem 1rem;
    margin: 0.5rem 0.5rem;
  }
</style>