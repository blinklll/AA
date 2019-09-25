<template>
	
	<view class="content">
		<view class="index-top">
			<view class="top-state">AA一点</view>
			<view class="top-adder"><img src="/static/icon_dz.png" alt=""> 铜山路万达五号楼</view>
			<view class="search">
				<img src="/static/icon_ss.png" alt="">
				<input type="text" value="" placeholder="请输入想搜索的内容" />
			</view>

		</view>
		<view class="index-content">
			<view class="circle-pic"></view>
			<view class="content-class">
				<view class="class-box">
					<view class="food-class">
						<img src="/static/btn_hb.png" alt="">
						<view>汉堡披萨</view>
					</view>
					<view class="food-class">
						<img src="/static/btn_yp.png" alt="">
						<view>水果蔬菜</view>
					</view>
					<view class="food-class">
						<img src="/static/btn_tp.png" alt="">
						<view>日韩料理</view>
					</view>
					<view class="food-class">
						<img src="/static/btn_sk.png" alt="">
						<view>快餐简餐</view>
					</view>
				</view>
				<view class="class-box">
					<view class="food-class">
						<img src="/static/btn_sg.png" alt="">
						<view>甜品蛋糕</view>
					</view>
					<view class="food-class">
						<img src="/static/btn_ll.png" alt="">

						<view>饮品</view>
					</view>
					<view class="food-class">
						<img src="/static/btn_ks.png" alt="">
						<view>烧烤</view>
					</view>
					<view class="food-class">
						<img src="/static/btn_kc.png" alt="">
						<view>快餐简餐</view>
					</view>
				</view>
			</view>
			<view class="content-business">
				<view class="pushbus">商家推荐</view>
				<view class="bus-msg">
					<view>销量</view>
					<view>价格</view>
					<view>评价</view>
				</view>
				<view class="business">
					<view class="bus-img"></view>
					<view class="bus-data">
						<view class="shop-name">汉堡王</view>
						<view>铜山万达广场&nbsp;&nbsp;快餐</view>
						<view class="shop-lable">
							
						</view>
						<view>6141人来过</view>
					</view>
					<view class="howfar">
						<view>30分钟&nbsp;&nbsp;3.9km</view>
					</view>
				</view>
				<view class="business">
					<view class="bus-img"></view>
					<view class="bus-data">
						<view class="shop-name">汉堡王</view>
						<view>铜山万达广场&nbsp;&nbsp;快餐</view>
						<view class="shop-lable">
							
						</view>
						<view>6141人来过</view>
					</view>
					<view class="howfar">
						<view>30分钟&nbsp;&nbsp;3.9km</view>
					</view>
				</view>
				<view class="business">
					<view class="bus-img"></view>
					<view class="bus-data">
						<view class="shop-name">汉堡王</view>
						<view>铜山万达广场&nbsp;&nbsp;快餐</view>
						<view class="shop-lable">
							
						</view>
						<view>6141人来过</view>
					</view>
					<view class="howfar">
						<view>30分钟&nbsp;&nbsp;3.9km</view>
					</view>
				</view>
			</view>

		</view>
		
		<view class="index-foot">
			<view>
				<view class="food-class nav-item ">
					<img src="/static/tab_sy_y.png" alt="">
					<view class="red">首页</view>
				</view>
			</view>
			<view>
				<view class="food-class nav-item">
					<img src="/static/tab_dt_n.png" alt="">
					<view>动态</view>
				</view>
			</view>
			<view>
				<view class="food-class nav-item">
					<img src="/static/tab_dd_n.png" alt="">
					<view>订单</view>
				</view>
			</view>
			<view>
				<view class="food-class nav-item">
					<img src="/static/tab_wd_n.png" alt="">
					<view>我的</view>
				</view>
			</view>

		</view>



</view>
</template>

<script>
	export default {
		data() {
			return {
				title: 'Hello'
			}
		},
		onLoad() {

		},
		methods: {

		}
	}
</script>

<style>
	.war{
		position: relative;
	}
	.content {
		position: relative;

		height: 100vh;
		display: flex;
		flex-direction: column;
		justify-content: space-between;
	}

	.index-content {
		z-index: 1;
		margin-top: 200upx;

		flex-grow: 1;
		background-color: rgba(223, 49, 72, 0);
	}

	.index-top {
		z-index: 3;
		position: fixed;
		top:0;
		left: ;
		

		padding: 50upx 20upx 0;
		color: #fff;
		background-color: rgba(223, 49, 72, 1);
		height: 210upx;
		width:100%;



	}

	.top-state {
		line-height: 36upx;
		font-size: 30upx;
		font-weight: 700;
	}

	.top-adder {
		margin: 16upx 0;
		height: 40upx;
		line-height: 40upx;
		font-size: 24upx;
	}

	.top-adder img {
		vertical-align: middle;
		height: 30upx;
		width: 26upx;
	}

	.search {
		background-color: #fff;
		display: flex;
		height: 60upx;
		
		border-radius: 30upx;
		margin-right: 20px;
		padding: 0 20upx;
		color: #333333;
	}

	.search img {
		margin-top: 10upx;
		margin-right: 20upx;
		vertical-align: middle;
		height: 34upx;
		line-height: 34upx;
		width: 34upx;

	}

	.circle-pic {
		height: 320upx;
	}

	.content-class {

		width: 750upx;

	}

	.class-box {
		padding: 20upx 0;
		height: 150upx;
		display: flex;
		align-items: center;
		justify-content: space-around;
	}

	.food-class {
		display: flex;
		flex-direction: column;

		width: 100upx;
		font-size: 24upx;
		align-content: center;
	}

	.food-class img {
		height: 100upx;
		width: 100upx;
	}

	.food-class view {

		margin: 0 auto;
		color: #333333;
	}

	/*商家推荐----------------------------  */
	.content-business {
		border-top: 10upx solid #f5f5f5;
		padding: 0 34upx;
		margin-bottom:160upx ;
	}

	.pushbus {
		color: #000;
		height: 60upx;
		line-height: 60upx;
		font-size: 36upx;
		font-weight: 600;
	}

	.bus-msg {
		display: flex;
		justify-content: space-between;
		font-size: 24upx;
		line-height: 44upx;
		height: 44upx;
	}

	.business {
		display: flex;
		height: 160upx;
		margin-top: 20upx;
		
	}

	.bus-img {
		height: 160upx;
		width: 140upx;
		border-radius: 30upx;
		background-color: #007AFF;
	}
	.bus-data{
		display: flex;
		flex-direction: column;
		align-items: flex-start;
		justify-content: space-between;
		margin: 10upx 10upx ;
		color: #99999;
		font-size: 24upx;
		
	}
	.shop-name{
		color: #000000;
		font-size: 30upx;
		flex-grow: 1;
	}
	.howfar{
		color: #999;
		margin: 60upx  0 0 180upx;
		font-size: 24upx;
	}

	/* 底部导航栏-------------------------- */
	.index-foot {
		position: fixed;
		left: 0;
		bottom:0;
		display: flex;
		justify-content: space-around;
		align-items: center;
		z-index: 2;

		background-color: #fff;
		box-shadow: 3upx 0 0 0 #111;
		height: 120upx;
		width: 100%;
	}
	
	.nav-item {
		display: flex;
		flex-direction: column;
	
		width: 50upx;
		font-size: 24upx;
		align-content: center;
	}
	
	.nav-item img {
		height: 50upx;
		width: 50upx;
	}
	
	.nav-item view {
		font-size: 26upx;
	
		margin: 0 auto;
		color: #333333;
	}
	 .red{
		color: #f00 !important;
	}


	/* .index-top::after {
		content: '';
		width: 100%;
		height: 100px;
		position: absolute;
		left: 0;
		top: 160upx;
		z-index: -2;
		border-radius: 0 0 50% 50%;
		background: linear-gradient(#fe4245, #fb144e);
		;

	} */
</style>
