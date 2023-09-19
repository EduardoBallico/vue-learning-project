<template>
	<form class="login">
    	<h1>Login page</h1>
    	<h1> {{ login }} </h1>
    	<TextImput 
      		v-model="login"
			placeholder="Login"
    	/>
    	<ContButton />
  	</form>
</template>

<script setup>
  	import TextImput from '../components/TextInput.vue'
  	import { ref } from 'vue'

	const login = ref('')

</script>

<style scoped>
	.login {
    	min-height: 100vh;
    	display: flex;
    	align-items: center;
  	}
</style>
