<template>
	<input 
		type="text"
		placeholder=placeholder
		class="input"
	>
</template>

<script setup>
	const props = defineProps({
		placeholder: String
	}
	)
</script>

<style scoped>
	 .input {
		background-color: #fff;
		border: none;
		border-radius: 0.25rem;
		color: #41b883;
		font-size: 1.25rem;
		padding: 0.5rem 1rem;
		margin: 0.5rem 0.5rem;
	}
</style>