<template>
	<view class="content">
        <!-- <image class="logo" src="../../static/logo.png"></image> -->
		<video src="http://clips.vorwaerts-gmbh.de/big_buck_bunny.mp4" controls="controls" loop="true"></video>
		<view>
            <text class="title">{{title}}</text>
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
	.content {
		text-align: center;
		height: 400upx;
	}
    .logo{
        height: 200upx;
        width: 200upx;
        margin-top: 200upx;
    }
	.title {
		font-size: 36upx;
		color: #8f8f94;
	}
</style>
