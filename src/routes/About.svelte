<script>
	import ProyectCard from '$lib/components/ProyectCard.svelte';
</script>

<main>
	<h1>Creative Studio</h1>
	<p>
		Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam adipiscing elit, sed diam
	</p>
	<img src="/circle-orange.svg" alt="artica group" id="decorate-left" />
	<img src="/circle-orange.svg" alt="artica group" id="decorate-right" />
	<ProyectCard align="right" />
	<ProyectCard />
</main>

<style>
	main {
		width: 100%;
		min-height: 100vh;
		display: grid;
		align-content: flex-start;
		padding: 0 calc(172.5px + 32px);
		padding-top: 245px;
		position: relative;
		background-color: #ffffff;
		border-radius: 30px;
		overflow: hidden;
		position: relative;
		top: -30px;
	}
	h1 {
		font-family: 'Aeonik TRIAL';
		font-style: normal;
		font-weight: 400;
		font-size: 130px;
		line-height: 100%;
		text-align: center;
	}
	p {
		max-width: 1005px;
		font-family: 'Aeonik TRIAL';
		font-style: normal;
		font-weight: 400;
		font-size: 30px;
		line-height: 40px;
		text-align: center;
		margin-top: 38px;
		color: #646464;
		justify-self: center;
	}
	#decorate-left {
		position: absolute;
		left: -173px;
		top: 205px;
	}
	#decorate-right {
		position: absolute;
		right: -173px;
		top: 763px;
	}
</style>
