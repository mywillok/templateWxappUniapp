<template>
	<view class="store">
		<custom-nav :title="title" />
		<view class="content">
			{{ title }}
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				title: '关于状态'
			}
		}
	}
</script>

<style lang="scss" scoped>
	.store {
		@include page();
		.content {
			@include flex();
			font-size: 123rpx;
		}
	}
</style>
