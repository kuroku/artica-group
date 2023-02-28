<script lang="ts">
	import { scrollbarTop } from '$lib/stores/scrollbar';
	import Header from '../lib/components/Header.svelte';
	function scroll(e: any) {
		$scrollbarTop = e.target.scrollTop;
	}
</script>

<div id="app" on:scroll={scroll}>
	<Header />
	<slot />
</div>

<style>
	:global(*) {
		margin: 0;
		padding: 0;
		box-sizing: border-box;
	}
	#app {
		width: 100%;
		height: 100%;
		background-size: cover;
		position: absolute;
		top: 0;
		left: 0;
		overflow: auto;
	}
</style>
