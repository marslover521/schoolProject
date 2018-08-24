<template>
	<div id="app">
		<router-view></router-view>
		<MyOrder></MyOrder>
	</div>
</template>

<script>
	import PersonalIndex from './components/personal/index';
	import MyOrder from './components/personal/myOrder';
	export default {
		name: 'app',
		components: {
			PersonalIndex,
			MyOrder
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