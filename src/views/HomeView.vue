<template>
  <main>
    <div class="about">
      <h1>Home</h1>
      <ContButton />
    </div>
  </main>
</template>

<script setup>
  import ContButton from '../components/ContButton.vue'
</script>

<style scoped>
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
</style>