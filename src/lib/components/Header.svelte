<script>
	import { scrollbarTop } from '$lib/stores/scrollbar';
	import { fly } from 'svelte/transition';
	import Button from './Button.svelte';
</script>

{#if $scrollbarTop === 0}
	<header transition:fly={{ duration: 180, y: -100 }}>
		<img src="/logo/white.svg" alt="artica" class="logo" />
		<menu>
			<Button>Nosotros</Button>
			<Button>Nosotros</Button>
			<Button outline>Portafolio</Button>
		</menu>
	</header>
{:else}
	<header class="white" transition:fly={{ duration: 180, y: -100 }}>
		<button>Trabajemos juntos</button>
		<img src="/logo/black.svg" alt="artica" class="logo" />
		<img src="/menu.svg" alt="artica group" class="icon" />
	</header>
{/if}

<style>
	header {
		width: 100%;
		height: 140px;
		position: fixed;
		top: 0;
		display: flex;
		justify-content: space-between;
		z-index: 99;
	}
	header.white {
		background-color: white;
		align-items: center;
		padding: 0 40px;
	}
	.white img.logo {
		margin-top: 0;
		margin-left: 0;
	}
	img.logo {
		margin-top: 40px;
		margin-left: 44px;
		height: 21px;
	}
	button {
		width: 277px;
		height: 40px;
		background: linear-gradient(255.38deg, #ff8002 12.02%, #f53004 87.77%);
		border-radius: 10px;
		border: none;
		font-family: 'Space Grotesk';
		font-style: normal;
		font-weight: 400;
		font-size: 20px;
		color: white;
	}
	menu {
		display: flex;
		gap: 20px;
		margin-right: 40px;
		margin-top: 40px;
	}
</style>
