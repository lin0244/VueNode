<template>
	<div class="app-wraper wraper">
		<router-view></router-view>
	</div>
</template>

<script type="text/ecmascript-6">
	export default {
		data () {
			return {

			};
		},
		mounted () {
			this.$router.push({name: 'GlobalCouponIndex'});
		}
	}
</script>

<style lang="less" rel="stylesheet/less">
	body {
		background: #fafafa;
	}
</style>