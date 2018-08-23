<template>
	<div id="app">
		<router-view></router-view>
		<PersonalIndex></PersonalIndex>
	</div>
</template>

<script>
	import PersonalIndex from './components/personal/index';
	export default {
		name: 'app',
		components: {
			PersonalIndex
		}
	}
</script>

<style>
	@import '/static/css/common.css';
	#app {
		font-family: 'Avenir', Helvetica, Arial, sans-serif;
		height: 100%;
	}
</style>