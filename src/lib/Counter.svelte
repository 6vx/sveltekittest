<script lang="ts">
	let count: number = 0;

	const increment = () => {
		count += 1;
	};
</script>

<button on:click={increment}>
	Clicks: {count}
</button>

<style>
	button {
		font-family: inherit;
		font-size: inherit;
		padding: 1em 2em;
		color: white;
		background-color: grey;
		border-radius: 2em;
		border: 2px solid darkslategray;
		outline: none;
		width: 200px;
		font-variant-numeric: tabular-nums;
	}

	button:focus {
		border: 2px solid white;
	}

	button:active {
		background-color: grey;
	}
</style>