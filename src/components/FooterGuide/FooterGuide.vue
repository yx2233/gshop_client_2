<template>
	<div class="footer_guide top-border-1px">
		<!-- :class="{on:true/false}" -->
		<span class="guide_item" :class="{on:'/msite'===$route.path}" @click="goTo('/msite')">
			<span class="item_icon">
				<i class="iconfont icon-waimai"></i>
			</span>
			<span>首页</span>
		</span>
		<span class="guide_item" :class="{on:'/search'===$route.path}" @click="goTo('/search')">
			<span class="item_icon">
				<i class="iconfont icon-search"></i>
			</span>
			<span>搜索</span>
		</span>
		<span class="guide_item" :class="{on:'/order'===$route.path}" @click="goTo('/order')">
			<span class="item_icon">
				<i class="iconfont icon-dingdan"></i>
			</span>
			<span>订单</span>
		</span>
		<span class="guide_item" :class="{on:'/profile'===$route.path}"  @click="goTo('/profile')">
			<span class="item_icon">
				<i class="iconfont icon-geren"></i>
			</span>
			<span>我的</span>
		</span>
	</div>
</template>

<script>
	export default{
		data(){
			return {
				
			}
		},
		methods:{
			goTo(path){
				this.$router.push(path);
			}
		}
	}
</script>

<style>
	.footer_guide{
		width: 100%;
		height: 50px;
		background-color: #fff;
		
		position: fixed;
		left: 0;
		right: 0;
		bottom: 0;
		
		display: flex;
		z-index: 100;
	}
	.top-border-1px::before{
		content: '';
		width: 100%;
		height: 2px;
		background-color: #e4e4e4;
		
		position: absolute;
		bottom: 50px;
		left: 0;
		right: 0;
		
		z-index: 200;
	}
	.footer_guide .guide_item{
		display: flex;
		flex: 1;
		flex-direction: column;
		align-items: center;
		margin: 5px;
		color: #999999;
	}
	.guide_item.on{
		color: #02a774;
	}
	.footer_guide .guide_item span{
		margin-top: 2px;
		margin-bottom: 2px;
		font-size: 14px;
	}
	.footer_guide .guide_item .iconfont{
		font-size: 22px;
	}
</style>
	
	
	
	
	
	
	
	<!-- .footer_guide{
		width: 100%;
		height: 50px;
		background: #fff;
		
		position: fixed;
		left: 0;
		right: 0;
		bottom: 0;
		
		display: flex;
		z-index: 100;
	}
	.top-border-1px::before{
		content: '';
		width: 100%;
		height: 1px;
		background-color: #e4e4e4;
		position: absolute;
		left: 0;
		right: 0;
		z-index: 200;
	}
	.footer_guide .guide_item{
		display: flex;
		flex: 1;
		flex-direction: column;
		align-items: center;
		text-align: center;
		margin: 5px;
		color: #999999;
	}
	.footer_guide .guide_item span{
		margin-top: 2px;
		margin-bottom: 2px;
		font-size: 15px;
	} -->
	
	
	
	
	
	
	
	
	
	
	<!-- .footer_guide{
		width: 100%;
		height: 50px;
		position: fixed;
		left: 0;
		right: 0;
		bottom: 0;
		display: flex;
		background-color: #fff;
		z-index: 100;
	}
	
	.top-border-1px::before{
		content: '';
		width: 100%;
		height: 1px;
		background-color:#e4e4e4 ;
		position: absolute;
		left: 0;
		right: 0;
		z-index: 200;
	}
	
	.guide_item{
		display: flex;
		flex: 1;
		flex-direction: column;
		align-items: center;
		text-align: center;
		margin:5px;
		color: #999999;
	}
	.guide_item.on{
		color: #02a774;
	}
	.guide_item span{
		font-size: 12px;
		margin-top: 2px;
		margin-bottom: 2px;
	}
	.guide_item span .iconfont{
		font-size: 22px;
	} -->

