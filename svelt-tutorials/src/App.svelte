<script>
	let count = 0;
	// reactive declarations 

	$: doubled = count * 2;
</script>

<p>{count} doubled is {doubled}</p>
<!-- {double} is reactive values -->
<!-- {doubled} replaces {count * 2} and prevents duplicate code -->