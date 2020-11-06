<template>
	<div class="msite">
		<!-- 首页头部 -->
		<header class="header">
			<a class="header_search">
				<i class="iconfont icon-sousuo"></i>
			</a>
			<a class="header_title">
				<span class="header_title_text ellipsis">昌平区北七家</span>
				<!-- <span class="header_title_text ellipsis">昌平区北七家宏福科技园(337省道北)</span> -->
			</a>
			<a class="header_login">
				<span class="header_login_text">登录|注册</span>
			</a>
		</header>
		
		<!-- 首页导航 -->
		<nav class="msite_nav border-1px">
			<div class="swiper-container">
				<div class="swiper-wrapper">
					<div class="swiper-slide">
						<a href="" class="link_to_food">
							<div class="food_container">
								<img src="./images/nav/1.jpg" alt="">
							</div>
							<span>甜品饮品</span>
						</a>
						<a href="" class="link_to_food">
							<div class="food_container">
								<img src="./images/nav/2.jpg" alt="">
							</div>
							<span>商超便利</span>
						</a>
						<a href="" class="link_to_food">
							<div class="food_container">
								<img src="./images/nav/3.jpg" alt="">
							</div>
							<span>美食</span>
						</a>
						<a href="" class="link_to_food">
							<div class="food_container">
								<img src="./images/nav/4.jpg" alt="">
							</div>
							<span>简餐</span>
						</a>
						<a href="" class="link_to_food">
							<div class="food_container">
								<img src="./images/nav/5.jpg" alt="">
							</div>
							<span>新店特惠</span>
						</a>
						<a href="" class="link_to_food">
							<div class="food_container">
								<img src="./images/nav/6.jpg" alt="">
							</div>
							<span>准时达</span>
						</a>
						<a href="" class="link_to_food">
							<div class="food_container">
								<img src="./images/nav/7.jpg" alt="">
							</div>
							<span>预订早餐</span>
						</a>
						<a href="" class="link_to_food">
							<div class="food_container">
								<img src="./images/nav/8.jpg" alt="">
							</div>
							<span>土豪推荐</span>
						</a>
					</div>
					<!-- <div class="swiper-slide">
						<a href="" class="link_to_food">
							<div class="food_container">
								<img src="./images/nav/1.jpg" alt="">
							</div>
							<span>甜品饮品</span>
						</a>
						<a href="" class="link_to_food">
							<div class="food_container">
								<img src="./images/nav/2.jpg" alt="">
							</div>
							<span>商超便利</span>
						</a>
						<a href="" class="link_to_food">
							<div class="food_container">
								<img src="./images/nav/3.jpg" alt="">
							</div>
							<span>美食</span>
						</a>
						<a href="" class="link_to_food">
							<div class="food_container">
								<img src="./images/nav/4.jpg" alt="">
							</div>
							<span>简餐</span>
						</a>
						<a href="" class="link_to_food">
							<div class="food_container">
								<img src="./images/nav/5.jpg" alt="">
							</div>
							<span>新店特惠</span>
						</a>
						<a href="" class="link_to_food">
							<div class="food_container">
								<img src="./images/nav/6.jpg" alt="">
							</div>
							<span>准时达</span>
						</a>
						<a href="" class="link_to_food">
							<div class="food_container">
								<img src="./images/nav/7.jpg" alt="">
							</div>
							<span>预订早餐</span>
						</a>
						<a href="" class="link_to_food">
							<div class="food_container">
								<img src="./images/nav/8.jpg" alt="">
							</div>
							<span>土豪推荐</span>
						</a>
					</div> -->
				</div>
				<div class="swiper-pagination"></div>
			</div>
		</nav>
		
		<!-- 首页附近商家 -->
		<div class="msite_shop_list">
			<div class="shop_header">
				<i class="iconfont icon-xuanziang"></i>
				<span class="shop_header_title">附近商家</span>
			</div>
			<div class="shop_container">
				<ul>
					<li>
						<a href="">
							<div class="shop_left">
								<img class="shop_img" src="./images/nav/1.jpg" alt="">
							</div>
							<div class="shop_right">
								<section class="shop_detail_header">
									<h4 class="shop_title">锄禾日当午，汗滴禾下土</h4>
									<ul class="shop_detail_ul">
										
									</ul>
								</section>
							</div>
						</a>
					</li>
				</ul>
			</div>
		</div>
	</div>
</template>

<script>
	export default{
		
	}
</script>

<style>
	.msite{
		width: 100%;
	}
	
	
	
	
	
	.header{
		width: 100%;
		height: 45px;
		background-color: #02A774;
		box-sizing: border-box;
		
		position: fixed;
		top: 0;
		left: 0;
		right: 0;
		z-index: 100;
		
		display: flex;
		justify-content: space-between;
		align-items: center;
		padding-left:15px;
		padding-right:15px;
	}
	.icon-sousuo{
		color: #fff;
		font-size: 25px;
	}
	.header_title_text{
		color: #fff;
		font-size: 20px;
	}
	.header_login_text{
		color: #fff;
		font-size: 14px;
	}
	
	.msite_nav{
		margin-top: 45px;
		height: 200px;
		background-color: #fff;
		border-bottom: 1px solid #e4e4e4;
	}
	.swiper-container,.swiper-wrapper{
		width: 100%;
		height: 100%;
	}
	.swiper-slide{
		display: flex;
		flex-wrap: wrap;
		justify-content: center;
		align-items: center;
		text-align: center;
	}
	.link_to_food{
		width: 24%;
		margin-bottom: 10px;
	}
	.food_container{
		padding-bottom: 10px;
	}
	.food_container img{
		width: 50px;
		height: 50px;
	}
	
	
	
	/* .header{
		width: 100%;
		height: 45px;
		background: #02A774;
		position: fixed;
		top: 0;
		left: 0;
		right: 0;
		z-index: 100;
	}
	
	.header_search{
		width: 10%;
		height: 50%;
		position: absolute;
		top: 50%;
		left: 15px;
		transform: translateY(-50%);
	}
	.icon-sousuo{
		font-size: 25px;
		color: #fff;
	}
	.header_title{
		width: 50%;
		position: absolute;
		left: 50%;
		top: 50%;
		transform: translate(-50%,-50%);
		text-align: center;
	}
	.header_title_text{
		font-size: 20px;
		color: #fff;
	}
	.ellipsis{
	  overflow: hidden;
	  text-overflow: ellipsis;
	  white-space: nowrap;
	}
	.header_login{
		position: absolute;
		top: 50%;
		right: 15px;
		transform: translateY(-50%);
	}
	.header_login_text{
		font-size: 14px;
		color: #fff;
	} 
	
	.msite_nav{
		margin-top: 45px;
		height: 200px;
		background-color: #fff;
		border-bottom: 1px solid #e4e4e4;
	}
	.swiper-container,.swiper-wrapper{
		width: 100%;
		height: 100%;
	}
	.swiper-slide{
		display: flex;
		justify-content: center;
		align-items: flex-start;
		flex-wrap: wrap;
	}
	.link_to_food{
		width: 25%;
	}
	.food_container{
		display: block;
		width: 100%;
		text-align: center;
		padding-bottom: 10px;
		font-size: 0;
	}
	
	.food_container img{
		display: inline-block;
		width: 50px;
		height: 50px;
	}
	.link_to_food span{
		text-align: center;
		display: block;
		width: 100%;
		font-size: 13px;
		color: #666;
		border: 1px solid red;
	}
	
	*/
</style>
