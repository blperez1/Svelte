<!-- using props: must export variables from other components -->
<script>
	import Nested from './Nested.svelte'
</script>

<Nested answer = {42}/>
<Nested />