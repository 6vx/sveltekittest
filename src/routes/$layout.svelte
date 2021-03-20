<script>

//import Blog from "./blog.svelte";

</script>

<svelte:head>
		<title>deathMetta</title>
</svelte:head>

<nav>
    <h1>deathMetta</h1>
</nav>

<slot></slot>

<footer>
	<a href="home">Home</a>
    <a href="quotes">Quotes</a>
    <a href="lifestyle">Lifestyle</a>
    <a href="notes">Notes</a>
    <p>Made by <a href="https://kitebot.ca">Kitebot</a>.</p>
</footer>

<style>
    :root {
		font-family: monospace, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell,
			'Open Sans', 'Helvetica Neue', sans-serif;
		background-color: black;
		color: white;
	}
    h1 {
		color: pink;
		margin: 1rem auto;
		max-width: 14rem;
	}
    nav {
        width: 100%;
        text-align: center;
    }
    a {
        color: pink;
    }
    a:visited {
        color: hotpink;
    }
    footer {
        width: 100%;
        text-align: center;
        position:absolute;
        bottom: 0;
    }
</style>