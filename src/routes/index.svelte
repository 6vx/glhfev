<script context="module">
	export const prerender = true;
</script>

<script>
	import Counter from '$lib/Counter.svelte';
</script>

<svelte:head>
	<title>GLHFEV</title>
</svelte:head>

<section>
	<h1><span class="yellow">GL</span> <span class="orange">HF</span> <span class="green">EV</span></h1>

	<h2>Fiddlin' w/ widgets</h2>

	<Counter />
</section>

<style>
	.yellow { color: #ff0; }
	.orange { color: #f90; }
	.green { color: #0f0; }

	section {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		flex: 1;
	}

	h1 {
		width: 100%;
	}

	/* .welcome {
		position: relative;
		width: 100%;
		height: 0;
		padding: 0 0 calc(100% * 495 / 2048) 0;
	}

	.welcome img {
		position: absolute;
		width: 100%;
		height: 100%;
		top: 0;
		display: block;
	} */
</style>
