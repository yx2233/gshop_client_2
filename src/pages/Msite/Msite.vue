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
				<i class="iconfont icon-xuanxiang"></i>
				<span class="shop_header_title">附近商家</span>
			</div>
			<div class="shop_container">
				<ul class="shop_list">
					<li class="shop_li">
						<a href="">
							<div class="shop_left">
								<img class="shop_img" src="./images/nav/1.jpg" alt="">
							</div>
							<div class="shop_right">
								<section class="shop_detail_header">
									<h4 class="shop_title ellipsis">锄禾日当午，汗滴禾下土</h4>
									<ul class="shop_detail_ul">
										<li class="supports">保</li>
										<li class="supports">准</li>
										<li class="supports">票</li>
									</ul>
								</section>
								<section class="shop_rating_order">
									<section class="shop_rating_order_left">
										<div class="str str-24">
											<span class="star-item on"></span>
											<span class="star-item on"></span>
											<span class="star-item on"></span>
											<span class="star-item half"></span>
											<span class="star-item off"></span>
										</div>
										<!-- <div class="rating_section">3.6</div>
										<div class="order_section">月售106单</div> -->
										<span class="rating_section">3.6</span>
										<span class="order_section">月售106单</span>
									</section>
									<section class="shop_rating_order_right">
										<span class="delivery_style delivery_left">硅谷专送</span>
										<!-- <span class="delivery_style delivery_right">硅谷专送</span> -->
									</section>
								</section>
								<section class="shop_distance">
									<p class="shop_delivery_msg">
										<span>￥20元起送</span>
										<span>/</span>
										<span>配送费￥5</span>
									</p>
								</section>
							</div>
						</a>
					</li>
					<li class="shop_li">
						<a href="">
							<div class="shop_left">
								<img class="shop_img" src="./images/nav/1.jpg" alt="">
							</div>
							<div class="shop_right">
								<section class="shop_detail_header">
									<h4 class="shop_title ellipsis">锄禾日当午，汗滴禾下土</h4>
									<ul class="shop_detail_ul">
										<li class="supports">保</li>
										<li class="supports">准</li>
										<li class="supports">票</li>
									</ul>
								</section>
								<section class="shop_rating_order">
									<section class="shop_rating_order_left">
										<div class="str str-24">
											<span class="star-item on"></span>
											<span class="star-item on"></span>
											<span class="star-item on"></span>
											<span class="star-item half"></span>
											<span class="star-item off"></span>
										</div>
										<!-- <div class="rating_section">3.6</div>
										<div class="order_section">月售106单</div> -->
										<span class="rating_section">3.6</span>
										<span class="order_section">月售106单</span>
									</section>
									<section class="shop_rating_order_right">
										<span class="delivery_style delivery_left">硅谷专送</span>
										<!-- <span class="delivery_style delivery_right">硅谷专送</span> -->
									</section>
								</section>
								<section class="shop_distance">
									<p class="shop_delivery_msg">
										<span>￥20元起送</span>
										<span>/</span>
										<span>配送费￥5</span>
									</p>
								</section>
							</div>
						</a>
					</li>
					<li class="shop_li">
						<a href="">
							<div class="shop_left">
								<img class="shop_img" src="./images/nav/1.jpg" alt="">
							</div>
							<div class="shop_right">
								<section class="shop_detail_header">
									<h4 class="shop_title ellipsis">锄禾日当午，汗滴禾下土</h4>
									<ul class="shop_detail_ul">
										<li class="supports">保</li>
										<li class="supports">准</li>
										<li class="supports">票</li>
									</ul>
								</section>
								<section class="shop_rating_order">
									<section class="shop_rating_order_left">
										<div class="str str-24">
											<span class="star-item on"></span>
											<span class="star-item on"></span>
											<span class="star-item on"></span>
											<span class="star-item half"></span>
											<span class="star-item off"></span>
										</div>
										<!-- <div class="rating_section">3.6</div>
										<div class="order_section">月售106单</div> -->
										<span class="rating_section">3.6</span>
										<span class="order_section">月售106单</span>
									</section>
									<section class="shop_rating_order_right">
										<span class="delivery_style delivery_left">硅谷专送</span>
										<!-- <span class="delivery_style delivery_right">硅谷专送</span> -->
									</section>
								</section>
								<section class="shop_distance">
									<p class="shop_delivery_msg">
										<span>￥20元起送</span>
										<span>/</span>
										<span>配送费￥5</span>
									</p>
								</section>
							</div>
						</a>
					</li>
					<li class="shop_li">
						<a href="">
							<div class="shop_left">
								<img class="shop_img" src="./images/nav/1.jpg" alt="">
							</div>
							<div class="shop_right">
								<section class="shop_detail_header">
									<h4 class="shop_title ellipsis">锄禾日当午，汗滴禾下土</h4>
									<ul class="shop_detail_ul">
										<li class="supports">保</li>
										<li class="supports">准</li>
										<li class="supports">票</li>
									</ul>
								</section>
								<section class="shop_rating_order">
									<section class="shop_rating_order_left">
										<div class="str str-24">
											<span class="star-item on"></span>
											<span class="star-item on"></span>
											<span class="star-item on"></span>
											<span class="star-item half"></span>
											<span class="star-item off"></span>
										</div>
										<!-- <div class="rating_section">3.6</div>
										<div class="order_section">月售106单</div> -->
										<span class="rating_section">3.6</span>
										<span class="order_section">月售106单</span>
									</section>
									<section class="shop_rating_order_right">
										<span class="delivery_style delivery_left">硅谷专送</span>
										<!-- <span class="delivery_style delivery_right">硅谷专送</span> -->
									</section>
								</section>
								<section class="shop_distance">
									<p class="shop_delivery_msg">
										<span>￥20元起送</span>
										<span>/</span>
										<span>配送费￥5</span>
									</p>
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
	.shop_rating_order{
		width: 100%;
		display: flex;
		justify-content: space-between;
		margin-top: 18px;
		margin-bottom: 8px;
	}
	.shop_rating_order_left{
		/* color: #FF9A0D; */
		
	}
	/* 星星 */
	.star .star-item {
		display: inline-block;
		background-repeat: no-repeat;
	}
	
	.star.star-48 .star-item {
		width: 20px;
		height: 20px;
		margin-right: 22px;
		background-size: 20px 20px;
	}
	
	.star.star-48 .star-item:last-child {
		margin-right: 0;
	}
	
	.star.star-48 .star-item.on {
		background-image: url("./images/stars/star48_on@2x.png");
	}
	
	/* @media (-webkit-min-device-pixel-ratio: 3),
	(min-device-pixel-ratio: 3) {
		.star.star-48 .star-item.on {
			background-image: url("./images/stars/star48_on@3x.png");
		}
	} */
	
	.star.star-48 .star-item.half {
		background-image: url("./images/stars/star48_half@2x.png");
	}
	
	/* @media (-webkit-min-device-pixel-ratio: 3),
	(min-device-pixel-ratio: 3) {
		.star.star-48 .star-item.half {
			background-image: url("./images/stars/star48_half@3x.png");
		}
	} */
	
	.star.star-48 .star-item.off {
		background-image: url("./images/stars/star48_off@2x.png");
	}
	
	/* @media (-webkit-min-device-pixel-ratio: 3),
	(min-device-pixel-ratio: 3) {
		.star.star-48 .star-item.off {
			background-image: url("./images/stars/star48_off@3x.png");
		}
	} */
	
	.star.star-36 .star-item {
		width: 15px;
		height: 15px;
		margin-right: 6px;
		background-size: 15px 15px;
	}
	
	.star.star-36 .star-item:last-child {
		margin-right: 0;
	}
	
	.star.star-36 .star-item.on {
		background-image: url("./images/stars/star36_on@2x.png");
	}
	
	/* @media (-webkit-min-device-pixel-ratio: 3),
	(min-device-pixel-ratio: 3) {
		.star.star-36 .star-item.on {
			background-image: url("./images/stars/star36_on@3x.png");
		}
	} */
	
	.star.star-36 .star-item.half {
		background-image: url("./images/stars/star36_half@2x.png");
	}
	
	/* @media (-webkit-min-device-pixel-ratio: 3),
	(min-device-pixel-ratio: 3) {
		.star.star-36 .star-item.half {
			background-image: url("./images/stars/star36_half@3x.png");
		}
	} */
	
	.star.star-36 .star-item.off {
		background-image: url("./images/stars/star36_off@2x.png");
	}
	
	/* @media (-webkit-min-device-pixel-ratio: 3),
	(min-device-pixel-ratio: 3) {
		.star.star-36 .star-item.off {
			background-image: url("./images/stars/star36_off@3x.png");
		}
	} */
	
	.star.star-24 .star-item {
		width: 10px;
		height: 10px;
		margin-right: 3px;
		background-size: 10px 10px;
	}
	
	.star.star-24 .star-item:last-child {
		margin-right: 0;
	}
	
	.star.star-24 .star-item.on {
		background-image: url("./images/stars/star24_on@2x.png");
	}
	
	/* @media (-webkit-min-device-pixel-ratio: 3),
	(min-device-pixel-ratio: 3) {
		.star.star-24 .star-item.on {
			background-image: url("./images/stars/star24_on@3x.png");
		}
	} */
	
	.star.star-24 .star-item.half {
		background-image: url("./images/stars/star24_half@2x.png");
	}
	
	/* @media (-webkit-min-device-pixel-ratio: 3),
	(min-device-pixel-ratio: 3) {
		.star.star-24 .star-item.half {
			background-image: url("./images/stars/star24_half@3x.png");
		}
	} */
	
	.star.star-24 .star-item.off {
		background-image: url("./images/stars/star24_off@2x.png");
	}
	
	/* @media (-webkit-min-device-pixel-ratio: 3),
	(min-device-pixel-ratio: 3) {
		.star.star-24 .star-item.off {
			background-image: url("./images/stars/star24_off@3x.png");
		}
	} */
	
	.shop_rating_order_right{
		
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
	.header_title{
		width: 50%;
		position: absolute;
		left: 50%;
		top: 50%;
		transform: translate(-50%,-50%);
		text-align: center;
		
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
	.msite_shop_list{
		border-top:1px solid #e4e4e4;
		margin-top:10px;
		background-color: #fff;
	}
	.shop_header{
		padding:10px 10px 0 10px;
		color: #999;
	}
	.shop_header_title{
		font-size: 14px;
		line-height: 20px;
	}
	.shop_container{
		margin-bottom: 50px;
	}
	.shop_li{
		border-bottom: 2px solid green;
		/* border-bottom: 1px solid #f1f1f1; */
		width: 100%;
		box-sizing: border-box;
		padding: 15px 8px;
	}
	.shop_li a{
		display: flex;
		flex-wrap: nowrap;
	}
	.shop_li a .shop_left{
		width: 23%;
		height: 75px;
		padding-right: 10px;
	}
	.shop_img{
		display: block;
		width: 100%;
		height: 100%;
	}
	.shop_right{
		width: 77%;
	}
	.shop_detail_header{
		width: 100%;
		display: flex;
		justify-content: space-between;
		flex-wrap: nowrap;
	}
	.shop_title{
		width: 70%;
		color: #333;
		font-size: 16px;
		font-weight: 700;
		line-height: 16px;
	}
	/* .text_ellipsis{
		overflow: hidden;
		text-overflow: ellipsis;
		white-space: nowrap;
	} */
	
	.shop_title::before{
		content: '品牌';
		display: inline-block;
		color: #333;
		font-size: 11px;
		line-height: 11px;
		background-color: #ffd930;
		padding: 2px 2px;
		border-radius: 2px;
		margin-right: 5px;
	}
	.shop_detail_ul{
		width: 30%;
		display: flex;
		justify-content: flex-end;
	}
	.shop_detail_ul .supports{
		color: #999;
		font-size: 14px;
		border:1px solid #f1f1f1;
		border-radius: 2px;
		padding: 0 2px;
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
