<!-- if blocks -->
<script>
	import Info from './Info.svelte'

	const pkg = {
		name: 'svelte',
		version: 3,
		speed: 'blazing',
		website: 'https://svelte.dev'
	}
</script>

<!-- next two lines will do the exact same thing. -->
<Info {...pkg}/>
<Info name={pkg.name} version={pkg.version} speed={pkg.speed} website={pkg.website} />