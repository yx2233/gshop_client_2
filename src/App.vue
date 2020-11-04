<template>
	<div id="app">
		<!-- app -->
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
	
</style>