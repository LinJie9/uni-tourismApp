<template>
	<view class="">
		
		
		<up-button text="月落"></up-button>
		
	</view>
</template>

<script setup>
	import { getBanner } from '../../api/api.js';
	import { onLoad } from '@dcloudio/uni-app'
	
	
	onLoad(() => {
		getBanner().then(res => {
			console.log(res, 'res');
		})
	})
	
	
</script>

<style>
	
</style>
