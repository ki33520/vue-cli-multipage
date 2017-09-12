<template>
	<div class="topbar flex flex-hv-center">
		<div class="btn btn-service">
			<i class="icon icon-service"></i>
		</div>
		<div class="search-bar flex-item">
			<input type="text" placeholder="请输入关键字搜索" class="search-input" />
		</div>
		<div class="btn btn-search">
			<i class="icon icon-search"></i>
		</div>
	</div>
</template>

<script>
require('assets/css/common.css');

import Hello from 'components/Hello'

export default {
	components: {
		Hello
	}
}
</script>


