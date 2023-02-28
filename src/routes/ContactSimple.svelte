<main>
	<hgroup>
		<img src="/logo/black.svg" alt="artica group" />
		<h1>Call to action para captacion de leads/ email</h1>
	</hgroup>
	<form>
		<label for="">CORREO</label>
		<input type="text" placeholder="tunombre@mail.com" />
		<button>Suscribirse</button>
	</form>
</main>

<style>
	main {
		display: flex;
		height: 520px;
		border-radius: 30px;
		padding: 0 58px 0 98px;
		align-items: center;
		gap: 130px;
		background: white;
		position: relative;
		top: -30px;
		z-index: 3;
	}
	img {
		margin-bottom: 52px;
	}
	h1 {
		font-family: 'Space Grotesk';
		font-style: normal;
		font-weight: 400;
		font-size: 45px;
	}
	label {
		font-family: 'Space Grotesk';
		font-style: normal;
		font-weight: 400;
		font-size: 15px;
		grid-column: 1/2;
		grid-row: 1/2;
	}
	input {
		width: 504px;
		height: 103px;
		background: #f0f0f0;
		border-radius: 15px;
		font-family: 'Space Grotesk';
		font-style: normal;
		font-weight: 400;
		font-size: 15px;
		padding: 44px;
		border: none;
		grid-column: 1/2;
		grid-row: 2/3;
	}
	form {
		display: grid;
		grid-template-columns: 1fr auto;
		grid-template-rows: auto auto;
		row-gap: 17px;
		column-gap: 20px;
	}
	button {
		width: 290px;
		height: 103px;
		background: #ff8002;
		border-radius: 56px;
		color: white;
		font-family: 'Space Grotesk';
		font-style: normal;
		font-weight: 400;
		font-size: 20px;
		border: none;
		grid-column: 2/3;
		grid-row: 2/3;
	}
</style>
