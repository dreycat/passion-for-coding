<script context="module" lang="ts">
	export const prerender = true;
</script>

<script lang="ts">
</script>

<svelte:head>
	<title>Coding for passion</title>
  <meta name="description" content="Coding for passion community web page.">
  <meta name="keywords" content="web development, community, discord, coding for passion">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
	

	<meta property="og:title" content="Coding for passion">
	<meta property="og:description" content="Coding for passion community web page.">
	<meta content="./bg.png" property="og:image">
</svelte:head>

<section>
	Passion for coding
</section>

<style>
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

	.welcome {
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
	}
</style>
