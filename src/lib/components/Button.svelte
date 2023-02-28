<script lang="ts">
	export let outline: boolean = false;
</script>

<button class:outline>
	<slot />
</button>

<style>
	button {
		height: 80px;
		padding: 30px 50px;
		font-family: 'Space Grotesk';
		font-style: normal;
		font-weight: 400;
		font-size: 20px;
		line-height: 100%;
		background: linear-gradient(255.38deg, #ff8002 12.02%, #f53004 87.77%);
		border-radius: 60px;
		border: none;
		color: white;
		transition: 180ms ease-in;
		box-shadow: 0px 0px 0px rgba(0, 0, 0, 0);
	}
	button:hover {
		background: linear-gradient(109.81deg, #ff8002 13.49%, #f53004 76.89%);
		box-shadow: 0px 8px 6px rgba(0, 0, 0, 0.15);
		transition: 180ms ease-out;
	}
	button.outline {
		background: none;
		border: 1px solid #ffffff;
	}
</style>
