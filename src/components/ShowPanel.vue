<template>
	<div name="show-panel" class="show-panel">
		<router-view></router-view>
	</div>
</template>

<script>
export default {
	name: 'showPanel'
}
</script>

<style scoped>
	.show-panel {
		position: fixed;
		top: 0;
		/*left: px2rem(1080px);*/
		left: 0;
		width: 100%;
		height: 100%;
		z-index: 10;
		background-color: #f9f9fb;
	}
</style>
