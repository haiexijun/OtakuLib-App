<template>
	<view>
	<view class="stage1">
		<view class="content1">
			<view class="left">
				<image src="../../static/defaultHeadPhoto.jpg"></image>
			</view>
			<view class="right">
				<view class="top">
					<text class="username">请点击头像登录</text>
				</view>
				<view class="bottom">
					<text class="rolekey">用户类型:</text>
					<text class="rolevalue">请先登录</text>
				</view>
			</view>
		</view>
	</view>
	<view class="stage2" hover-class="hover" hover-start-time="0" hover-stay-time="100">
		<view class="left2">
			<view class="lefticon">
				<image class="img" src="../../static/edit.png"></image>
			</view>
			<view class="righttext">
				<text class="text">编辑个人资料</text>
			</view>
		</view>
		<view class="right2">
			<image class="righticon" src="../../static/right.png"></image>
		</view>
	</view>
	<view class="stage2" hover-class="hover" hover-start-time="0" hover-stay-time="100">
		<view class="left2">
			<view class="lefticon">
				<image class="img" src="../../static/donate.png"></image>
			</view>
			<view class="righttext">
				<text class="text">赞助和捐赠</text>
			</view>
		</view>
		<view class="right2">
			<image class="righticon" src="../../static/right.png"></image>
		</view>
	</view>
	<view class="stage3" hover-class="hover" hover-start-time="0" hover-stay-time="100">
		<view class="left2">
			<view class="lefticon">
				<image class="img" src="../../static/askbook.png"></image>
			</view>
			<view class="righttext">
				<text class="text">我要求书</text>
			</view>
		</view>
		<view class="right2">
			<image class="righticon" src="../../static/right.png"></image>
		</view>
	</view>
	<view class="stage3" hover-class="hover" hover-start-time="0" hover-stay-time="100">
		<view class="left2">
			<view class="lefticon">
				<image class="img" src="../../static/QQ.png"></image>
			</view>
			<view class="righttext">
				<text class="text">宅书库交流群</text>
			</view>
		</view>
		<view class="right2">
			<image class="righticon" src="../../static/right.png"></image>
		</view>
	</view>
	<view class="stage3" hover-class="hover" hover-start-time="0" hover-stay-time="100">
		<view class="left2">
			<view class="lefticon">
				<image class="img" src="../../static/advice.png"></image>
			</view>
			<view class="righttext">
				<text class="text">意见与反馈</text>
			</view>
		</view>
		<view class="right2">
			<image class="righticon" src="../../static/right.png"></image>
		</view>
	</view>
	<view class="stage3" hover-class="hover" hover-start-time="0" hover-stay-time="100">
		<view class="left2">
			<view class="lefticon">
				<image class="img" src="../../static/about.png"></image>
			</view>
			<view class="righttext">
				<text class="text">关于宅书库</text>
			</view>
		</view>
		<view class="right2">
			<image class="righticon" src="../../static/right.png"></image>
		</view>
	</view>
	</view>
</template>

<script>
</script>

<style>
	page{
		background-color: #f3f3f3;
	}
</style>
<style scoped>
	.stage1{
		width: 100%;
		height: 330upx;
		background-color: #ffffff;
		overflow: hidden;
	}
	.stage2{
		width: 100%;
		height: 100upx;
		background-color: #ffffff;
		margin-top: 15upx;
		overflow: hidden;
	}
	.stage3{
		width: 100%;
		height: 100upx;
		background-color: #ffffff;
		margin-top: 0upx;
		border-top: 1upx solid #e2e2e2;
		overflow: hidden;
	}
	.content1{
		background-color: #fff;
		width: 93%;
		margin: 0 auto;
		margin-top: 130upx;
		height: 150upx;
	}
	.left{
		width: 150upx;
		height: 150upx;
		background-color: aquamarine;
		float: left;
		border-radius: 30upx;
	}
	image{
		display: block;
		width: 100%;
		height: 100%;
		border-radius: 30upx;
	}
	.right{
		width: 450upx;
		height: 150upx;
		margin-left: 25upx;
		float: left;
	}
	.top{
		width: 100%;
		height: 50%;
	}
	.bottom{
		width: 100%;
		height: 50%;
	}
	.username{
		line-height: 75upx;
		font-size: 45upx;
		font-weight: 700;
	}
	.rolekey{
		line-height:90upx;
		font-family: Verdana, Geneva, Tahoma, sans-serif;
	}
	.rolevalue{
		line-height: 90upx;
		margin-left: 15upx;
	}
	.left2{
		width: 87%;
		height: 100%;
		float: left;
	}
	.right2{
		width: 13%;
		height: 100%;
		float: left;
	}
	.righticon{
		display: block;
		width: 30%;
		height: 35%;
		margin-left: 45upx;
		margin-top: 36upx;
	}
	.lefticon{
		width: 15%;
		height: 100%;
		float: left;
	}
	.righttext{
		width: 85%;
		height: 100%;
		float: left;
	}
	.text{
		margin-left: 5upx;
		line-height: 105upx;
		font-size: 38upx;
	}
	.img{
		display: block;
		width: 70%;
		height: 70%;
		margin: 0 auto;
		margin-top: 18upx;
	}
	.hover{
		background-color: #eaeaea;
	}
</style>