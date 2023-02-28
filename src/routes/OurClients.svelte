<script>
	import Button from '$lib/components/Button.svelte';
</script>

<main>
	<section>
		<h3>Call to action via contacto</h3>
		<Button outline>Portafolio</Button>
	</section>
	<img src="/wallpaper-banner.png" alt="" id="banner" />
	<h1>Nuestros Clientes</h1>
	<img src="/circle-blue.svg" alt="" id="circle-blue" />
	<figure>
		<img src="/logo-chrome.svg" alt="" />
		<img src="/logo-apple.svg" alt="" />
		<img src="/logo-css3.svg" alt="" />
		<img src="/logo-bitcoin.svg" alt="" />
		<img src="/logo-amazon.svg" alt="" />
	</figure>
</main>

<style>
	main {
		width: 100%;
		min-height: 100%;
		padding: 0 76px;
		position: relative;
		background-color: white;
		border-radius: 30px;
		padding-bottom: 168px;
		bottom: -30px;
		z-index: 3;
	}
	img#banner {
		width: 100%;
	}
	section {
		width: 100%;
		height: 298px;
		background: linear-gradient(267.89deg, #03c1ad -0.99%, rgba(1, 157, 185, 0.5) 103.7%);
		border-radius: 30px;
		display: flex;
		align-items: center;
		padding: 99px 83px;
		justify-content: space-between;
		margin-bottom: 226px;
	}

	img#circle-blue {
		position: absolute;
		left: -169px;
		margin-top: -120px;
	}

	h1 {
		font-family: 'Aeonik TRIAL';
		font-style: normal;
		font-weight: 400;
		font-size: 130px;
		text-align: center;
		margin-top: 178px;
	}

	h3 {
		max-width: 550px;
		font-family: 'Aeonik TRIAL';
		font-style: normal;
		font-weight: 700;
		font-size: 90px;
		color: white;
	}

	figure {
		width: 100%;
		display: flex;
		gap: 100px;
		opacity: 0.4;
		justify-content: center;
		margin-top: 104px;
	}
</style>
