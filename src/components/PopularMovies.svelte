<script>
	export let popular;
	import MovieCard from './MovieCard.svelte';
</script>

<h1>This is the Popular Movies</h1>

<div class="popular-movies">
	{#each popular as movie}
		<MovieCard {movie} />
	{/each}
</div>
