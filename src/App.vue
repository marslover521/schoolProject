<template>
	<div id="app">
		<router-view></router-view>
		<setting></setting>
	</div>
</template>

<script>
	import PersonalIndex from './components/personal/index';
	import test from './components/personal/test';
	import setting from './components/personal/setting';
	export default {
		name: 'app',
		components: {
			PersonalIndex,
			test,
			setting
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
