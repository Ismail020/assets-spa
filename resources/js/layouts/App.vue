<template>
	<div>
		<div>
			<router-link :to="{ name: 'Home' }">Home</router-link> |
			<router-link :to="{ name: 'About' }">About</router-link>
		</div>
		<router-view />
	</div>
</template>

<script setup>
</script>