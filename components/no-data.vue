<template>
	<view class="no-data animated fadeIn">
		<image class="no-data-img" src="@/static/image/no-data.png" mode="widthFix" lazy-load></image>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				
			};
		}
	}
</script>

<style lang="stylus" scoped>
.no-data{
	position absolute
	width 100%
	height 100%
	color #AAAAAA
	display flex
	flex-direction column
	align-items center
	justify-content center
	.no-data-img{
		width 50%
	}
}
</style>
