<template>
	<div class="home">
		<img alt="Vue logo" src="../assets/logo.png" />
		<HelloWorld msg="Welcome to Your Vue.js + TypeScript App" />
	</div>
</template>

<script lang="ts">
import Vue from 'vue';
import HelloWorld from '@/components/HelloWorld.vue'; // @ is an alias to /src

export default Vue.extend({
	name: 'Home',
	components: {
		HelloWorld,
	},
});
</script>
<style lang="scss" scoped>
.home {
	text-align: center;
	color: #2c3e50;
}
</style>
