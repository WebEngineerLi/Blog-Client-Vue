<template>
	<div class="header">
		{{ title }}
	</div>
</template>

<script>
export default {
	props: {
		title: String
	}
}
</script>
<style scoped>
@import './header.less';
</style>
