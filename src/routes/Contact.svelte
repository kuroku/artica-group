<script>
	import Button from '$lib/components/Button.svelte';
</script>

<main>
	<hgroup>
		<h1>Lleva tu marca al siguiente nivel</h1>
		<p>
			Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam adipiscing elit, sed diam
		</p>
	</hgroup>
	<form>
		<label for="name">NOMBRE</label>
		<div class="group-input">
			<input type="text" placeholder="Nombre" id="name" />
			<input type="text" placeholder="Apellido" id="apellido" />
		</div>
		<label for="email">CORREO</label>
		<input type="text" placeholder="tucorreo@mail.com" id="email" />
		<label for="phonenumber">NUMERO DE TELEFONO</label>
		<input type="text" placeholder="+58 414 100 000" id="phonenumber" />
		<label for="services">QUE SERVICIO TE INTERESA</label>
		<input type="text" placeholder="Marketing y videos promocionales" id="services" />
		<Button>Enviar</Button>
	</form>
</main>

<style>
	main {
		display: grid;
		grid-template-columns: 1fr 1fr;
		padding: 140px 140px;
		gap: 266px;
	}
	h1 {
		font-family: 'Aeonik TRIAL';
		font-style: normal;
		font-weight: 400;
		font-size: 130px;
		margin-bottom: 50px;
	}
	p {
		font-family: 'Aeonik TRIAL';
		font-style: normal;
		font-weight: 400;
		font-size: 30px;
		line-height: 40px;
	}
	form {
		display: grid;
		align-content: flex-start;
		background: #111111;
		border-radius: 30px;
		width: 665px;
		height: 878px;
		padding: 64px 45px;
	}
	.group-input {
		display: flex;
		gap: 45px;
	}
	form :global(button) {
		margin-top: 60px;
	}
	label {
		font-family: 'Space Grotesk';
		font-style: normal;
		font-weight: 400;
		font-size: 15px;
		margin-bottom: 15px;
	}
	input {
		width: 100%;
		background: none;
		height: 72px;
		border: 0.5px solid #666666;
		border-radius: 5px;
		font-family: 'Space Grotesk';
		font-style: normal;
		font-weight: 400;
		font-size: 13px;
		padding: 29px;
		margin-bottom: 45px;
	}
</style>
