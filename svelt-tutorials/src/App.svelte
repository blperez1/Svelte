<script>
	let numbers = [1, 2, 3, 4];

	function addNumber() {
		//array methods such as push and slice won't automatically update.
		//following line will not update number
		// numbers.push(numbers.length + 1);

		//following line fixes this issue
		numbers = [...numbers, numbers.length + 1];
	}
	$: sum = numbers.reduce((t, n) => t + n, 0);
</script>

<main>
	<p>{numbers.join('+')} = {sum}</p>
	<button on:click={addNumber}>Add a number</button>
</main>