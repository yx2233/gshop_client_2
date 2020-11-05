<template>
	<div id="app">
		<router-view/>
		<FooterGuide/>
	</div>
</template>
<script>
	import FooterGuide from "./components/FooterGuide/FooterGuide.vue"
	export default{
		data(){
			return {
				
			}
		},
		components:{
			FooterGuide
		},
		
	}
</script>
<style>
	#app{
		width: 100%;
		height: 100%;
		background: #F5F5F5;
	}
</style>