<script>
	let name = 'World';
	let src = './favicon.png'
</script>

<main>
	<img {src} alt='svelte icon'>
	<h1>Hello {name.toUpperCase()}!</h1>
</main>

<style>
	h1 {
		color: purple;
		font-family: 'Comic Sans MS', cursive;
		font-size: 2em;
	}
</style>
