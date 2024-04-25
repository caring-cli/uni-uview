<template>
	<div style="background: #f8f8f8;">
		
		<u-icon name="photo"></u-icon>

		<u-gap/>
		<u-section/>
		<u-button>默认按钮，size=default,shape=squard</u-button>
		<u-gap/>
		<u-button type="primary">设置主题:type=primary</u-button>
		<u-gap/>
		<u-button type="primary" ripple>水波纹:ripple</u-button>
		<u-gap/>
		<u-button type="primary" loading>loading</u-button>
		<u-gap/>
		<u-button type="error" loading>loading</u-button>
		<u-gap/>
		<u-button :hair-line="false">hair-line="false"</u-button>
		<u-gap/>
		<u-button type="primary" disabled>禁用:disabled</u-button>
		<u-gap/>
		<u-button type="primary" shape="circle">设置半圆:shape="circle"</u-button>
		<u-gap/>
		<u-button type="primary" shape="circle" plain>设置镂空:plain</u-button>
		<u-gap/>
		<u-button type="primary" size="medium">设置size:size="medium"</u-button>
		<u-button type="primary" size="mini">size="mini"</u-button>
	</div>
</template>

<script>
	export default {
		data() {
			return {
				value: '',
				type: 'text',
				border: true
			}
		},
	}
</script>

<style scoped>

</style>