<script>
	import Nested from './Nested.svelte'
	let name = 'World';
	let src = './favicon.png'
</script>

<main>
	<p>This is a paragraph.</p>
	<Nested/>
</main>

<style>
	p{
		color:purple;
		font-family: 'Comic Sans MS', cursive;
		font-size: 2em;
	}
</style>