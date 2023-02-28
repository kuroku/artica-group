<main>
	<h1>creative studio</h1>
	<p>
		CARACTERÍSTICAS DE LA LINEA GRÁFICA MINIMALISTA, MODERNA, DISRUPTIVA US O DE ELEMENTOS
		INTUITIVOS RESALTAR EL ENTORNO AUDIOVISUAL
	</p>

	<span> Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam </span>

	<img src="/text_init.svg" alt="artica group" loading="lazy" />
</main>

<style>
	main {
		width: 100%;
		min-height: 100vh;
		padding-top: 180px;
		padding-left: 60px;
		padding-right: 60px;
		display: grid;
		align-content: flex-start;
		gap: 32px;
		grid-template-columns: 1fr 1fr;
		background-image: url('/background/gradiant.png');
		background-size: cover;
	}
	h1 {
		grid-column: 1/2;
		font-family: 'Space Grotesk';
		font-style: normal;
		font-weight: 700;
		font-size: 250px;
		line-height: 100%;
		color: white;
	}
	p {
		grid-column: 1/2;
		width: 363px;
		color: white;
		font-family: 'Versatylo Rounded';
		font-style: normal;
		font-weight: 400;
		font-size: 10px;
		line-height: 100%;
		text-align: justify;
	}
	span {
		font-family: 'Aeonik TRIAL';
		font-style: normal;
		font-weight: 400;
		font-size: 50px;
		color: white;
	}
	img {
		width: 100%;
		grid-row: 1/2;
		grid-column: 2/3;
		place-self: center;
	}
</style>
