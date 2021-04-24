<template>
	<view class="content">
		<!-- 头部导航 -->
		<view class="text-area" v-for="(item,index) in arr" :key="index">
			{{item}}
		</view>
		<view class="text-area-boder"></view>
		<!-- 主体 -->
		<view class="body">
			<view class="box">

				<view class="box_block">
					<view class="box_block_top">
						cdf会员购北京 >
					</view>
					<view class="box_block_bottom">
						<view class="img_left">
							<view class="img"></view>
						</view>
						<view class="img_right">
							<view class="text">
								<view class="line_block">
									肌肤之钥光凝前霜37MLx2
								</view>
								<view class="line_block margin_left">
									￥178.00
								</view>
								<view class="">
									创建时间:2020-09-01 17:22:03
								</view>
								<view class="">
									锁单时间:2020-O9-01 17:22:03
								</view>
								<view class="">
									支付时间:
								</view>
							</view>

							<view class="btn">
								<button class="btn_1" type="default">再来一单</button>
								<button class="btn_2" type="default">分享得500积分</button>
							</view>
						</view>
					</view>
				</view>

				<view class="box_block">
					<view class="box_block_top">
						cdf会员购北京 >
					</view>
					<view class="box_block_bottom">
						<view class="img_left">
							<view class="img"></view>
						</view>
						<view class="img_right">
							<view class="text">
								<view class="line_block">
									肌肤之钥光凝前霜37MLx2
								</view>
								<view class="line_block margin_left">
									￥178.00
								</view>
								<view class="">
									创建时间:2020-09-01 17:22:03
								</view>
								<view class="">
									锁单时间:2020-O9-01 17:22:03
								</view>
								<view class="">
									支付时间:
								</view>
							</view>

							<view class="btn">
								<button class="btn_1" type="default">再来一单</button>
								<button class="btn_2" type="default">分享得500积分</button>
							</view>
						</view>
					</view>
				</view>
				<view class="box_block">
					<view class="box_block_top">
						cdf会员购北京 >
					</view>
					<view class="box_block_bottom">
						<view class="img_left">
							<view class="img"></view>
						</view>
						<view class="img_right">
							<view class="text">
								<view class="line_block">
									肌肤之钥光凝前霜37MLx2
								</view>
								<view class="line_block margin_left">
									￥178.00
								</view>
								<view class="">
									创建时间:2020-09-01 17:22:03
								</view>
								<view class="">
									锁单时间:2020-O9-01 17:22:03
								</view>
								<view class="">
									支付时间:
								</view>
							</view>

							<view class="btn">
								<button class="btn_1" type="default">再来一单</button>
								<button class="btn_2" type="default">分享得500积分</button>
							</view>
						</view>
					</view>
				</view>
				<view class="box_block">
					<view class="box_block_top">
						cdf会员购北京 >
					</view>
					<view class="box_block_bottom">
						<view class="img_left">
							<view class="img"></view>
						</view>
						<view class="img_right">
							<view class="text">
								<view class="line_block">
									肌肤之钥光凝前霜37MLx2
								</view>
								<view class="line_block margin_left">
									￥178.00
								</view>
								<view class="">
									创建时间:2020-09-01 17:22:03
								</view>
								<view class="">
									锁单时间:2020-O9-01 17:22:03
								</view>
								<view class="">
									支付时间:
								</view>
							</view>

							<view class="btn">
								<button class="btn_1" type="default">再来一单</button>
								<button class="btn_2" type="default">分享得500积分</button>
							</view>
						</view>
					</view>
				</view>

			</view>
		</view>
	</view>
	</view>

</template>

<script>
	export default {
		data() {
			return {
				arr: ["全部", "代下单", "待结算", "已结算", "已作废"],
			}
		},
		onLoad() {

		},
		methods: {}
	}
</script>

<style>
	.text-area {
		display: inline-block !important;
		width: 20%;
		height: 80rpx;
		line-height: 80rpx;
		text-align: center;
		margin-bottom: 40rpx;
		background-color: #4CD964;
	}

	.active {
		color: #ff0000;
		border-bottom: 1px solid #ff0000;
	}

	.text-area-boder {
		width: 20%;
		height: 5rpx;
		border-radius: 5rpx;
	}

	.box_block {
		box-sizing: border-box;
		text-align: center;
		width: 90%;
		margin: 30rpx auto;
		border-radius: 20rpx;
		background-color: #ffffff;
	}

	.box_block_top {
		text-align: left;
		width: 100%;
		line-height: 100rpx;
		margin-left: 60rpx;
		border-bottom: #e4e3e8;

	}

	.box_block_bottom {
		width: 100%;
		text-align: center;
		/* margin-bottom: 400rpx; */
		/* background-color: #007AFF; */
	}

	.img_left {
		display: inline-block;
		width: 10%;
		height: 100%;
	}

	.box_block_bottom .img {
		width: 200rpx;
		height: 200rpx;
		border-radius: 10rpx;
		margin: 0 auto;
		box-shadow: 0 0 1px #808080;
	}

	.img_right {
		width: 90%;
		height: 100%;
		display: inline-block;
	}

	.text {
		text-align: left;
		color: #C0C0C0;
	}

	.text view {
		margin: 6rpx auto;
	}

	.line_block {
		font-size: 16px;
		color: #111111;
		display: inline-block;
	}

	.margin_left {
		margin: 0 15%;
	}

	.btn {
		width: 10%;
		text-align: center;
	}

	.btn_1 {
		display: inline-block;
		width: 260rpx;
		font-size: 12px;
		border-radius: 100px;
		background-color: #FFFFFF;
		border: 1px solid #111111;
	}

	.btn_2 {
		display: inline-block;
		border-radius: 100px;
		width: 260rpx;
		font-size: 12px;
		border: 1px solid #ff0000;
		color: #ff0000;
		background-color: #FFFFFF;
	}
</style>
