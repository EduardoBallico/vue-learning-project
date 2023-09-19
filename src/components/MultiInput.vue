<template>
  <div>
    <select name="select" id="multi-select">
      <option 
        v-for="option in options"
        :key="option"
      > {{ option }} </option>
    </select>
  </div>
</template>

<script setup>
  
  defineProps({
    options: {
      type: Array,
      default: () =>["banana", "apple", "grape"]
    }
  })

</script>

<style lang="scss" scoped>
  #multi-select {
    width: 100%;
    height: 100%;
    padding: 0.5rem;
    border: 1px solid #ccc;
    border-radius: 0.25rem;
    font-size: 1rem;
    line-height: 1.5;
    color: #495057;
    background-color: #fff;
    background-clip: padding-box;
    transition: border-color 0.15s ease-in-out, box-shadow 0.15s ease-in-out;
  }
</style>