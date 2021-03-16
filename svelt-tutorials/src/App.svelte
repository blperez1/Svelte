<script>

let cats = [
	{ id: 'J---aiyznGQ', name: 'Keyboard Cat' },
	{ id: 'z_AbfPXTKms', name: 'Maru' },
	{ id: 'OUtn3pvWmpg', name: 'Henri The Existential Cat' }
];

</script>

<h1>The Famous Cats of Youtube</h1>

<!-- grab current index -->
<ul>
	{#each cats as cat, i}
		<li><a target="_blank" href="https://www.youtube.com/watch?v={cat.id}">
			{i + 1}: {cat.name}
		</a></li>
	<!-- close each block -->
	{/each}
</ul>