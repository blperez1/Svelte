<!-- if blocks -->
<script>
	let user = {loggedIn: false};

	function toggle() {
		user.loggedIn = !user.loggedIn;
	}
</script>

<!-- both if blocks are mutually exclusive. Replace with if/else -->
{#if user.loggedIn}
	<button on:click={toggle}>
		Log out
	</button>
{:else} 
	<button on:click={toggle}>
		Log in
	</button>
{/if}