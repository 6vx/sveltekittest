<script lang="ts">
	// import Counter from '$lib/Counter.svelte';
</script>

<main>
	<p>featured content</p>

	<p>support</p>

	<p>latest content</p>

	<p>quote content</p>

	<!-- <Counter /> -->
</main>

<style>
	main {
		text-align: center;
		padding: 1em;
		margin: 0 auto;
	}

	p {
		max-width: 14rem;
		margin: 2rem auto;
		line-height: 1.35;
	}

	@media (min-width: 480px) {
		h1 {
			max-width: none;
		}

		p {
			max-width: none;
		}
	}
</style>
