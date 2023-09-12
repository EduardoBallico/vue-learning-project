<template>
  <main>
    <div>
      <h1>Home</h1>
      <ContButton />
    </div>
  </main>
</template>

<script setup>
  import ContButton from '../components/ContButton.vue'
</script>

<style scoped>
  main {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
</style>