<script lang="ts">
	import Button from './Button.svelte';
	export let align: 'left' | 'right' = 'left';
</script>

<article class={align}>
	<img src="/arrow-title-{align}.svg" alt="" class="arrow-title" />
	<hgroup>
		<h2>Titulo proyecto nro. uno</h2>
		<p>
			Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam adipiscing elit, sed diam
		</p>
		<Button>Nosotros</Button>
	</hgroup>
	<figure>
		<img src="/wallpaper-proyect.png" alt="artica group" loading="lazy" />
		<img src="/wallpaper-proyect-surface.png" alt="artica group" class="surface" loading="lazy" />
		<img src="/indicador-marketing.svg" alt="artica group" id="marketing" />
		<img src="/indicador-strategy.svg" alt="artica group" id="strategy" />
	</figure>
</article>

<style>
	article {
		width: 100%;
		display: flex;
		gap: 136px;
		padding-bottom: 133px;
	}
	article.left {
		flex-direction: row-reverse;
	}
	hgroup,
	figure {
		margin-top: 77px;
	}
	h2 {
		font-family: 'Aeonik TRIAL';
		font-style: normal;
		font-weight: 400;
		font-size: 90px;
	}
	p {
		font-family: 'Aeonik TRIAL';
		font-style: normal;
		font-weight: 400;
		font-size: 30px;
		line-height: 40px;
		color: #646464;
		margin-top: 40px;
		margin-bottom: 30px;
	}
	figure {
		position: relative;
	}
	img.arrow-title {
		position: absolute;
	}
	.left img.arrow-title {
		left: -128px;
	}
	.right img.arrow-title {
		right: -128px;
	}
	img#marketing {
		position: absolute;
		left: 380px;
		top: -40px;
	}
	img#strategy {
		position: absolute;
		left: -65px;
		top: 90px;
	}
	img.surface {
		position: absolute;
		width: 263px;
		height: 468px;
		left: 240px;
		top: -50px;
	}
</style>
