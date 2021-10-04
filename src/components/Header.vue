<template>
	<header>
		<!-- class="header-bar-colors-container" -->
		<span class="header-color-area-1"></span>
		<span class="header-color-area-2"></span>
		<span class="header-color-area-3"></span>
		<span class="header-color-area-4"></span>
		<span class="header-color-area-5"></span>
	</header>
</template>
<script>
	export default {
		data() {
			return {};
		},
	};
</script>
<style scoped>
	header {
		/* .header-bar-colors-container */
		width: 100%;
		height: 10%;
		position: absolute;
		top: 0;
		left: 0;
		display: flex;
		flex-direction: row;
	}
	span {
		width: 20%;
		height: 20%;
	}
	.header-color-area-1 {
		background-color: var(--profile-section-color);
	}
	.header-color-area-2 {
		background-color: var(--resume-section-color);
	}
	.header-color-area-3 {
		background-color: var(--portfolio-section-color);
	}
	.header-color-area-4 {
		background-color: var(--testimonials-section-color);
	}
	.header-color-area-5 {
		background-color: var(--contacts-section-color);
	}
</style>
