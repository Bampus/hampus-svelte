<script>
	let name = "dear user";
    let count = 0;

	const increseCounter = () => {
		count ++ 
	}
</script>

<main>
	<h1>Hello {name}</h1>
	<h3>Counter: {count} </h3>
	<button on:click={increseCounter}>Press me please</button>
</main>

<style>
	main {
		display: flex;
		flex-direction: column;
		align-items: center;
	}

    h3 {
      font-size: 52px;
	}

	h1 {
		font-size: 72px;
		text-align: center;
	}
</style>
