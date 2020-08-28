<template>
	<div>
		<div class="content">
			<img src="../../assets/001.jpg" alt="">
			<p>周末去游泳吧</p>
		</div>
	</div>
</template>

<script>
	export default {
		name:'Photo'
	}
</script>

<style scoped="scoped">
	
	.content {
		width: 100%;
		height: 8rem;
		position: relative;
	}
	img {
		width: 100%;
		height: 8rem;
		
	}
	p {
		width: 100%;
		font-size: 0.75rem;
		color: #eee;
		background-color: rgba(0,0,0,.3);
		position: absolute;
		bottom: 0.05rem;
		left: 0.2rem;
	}
</style>
