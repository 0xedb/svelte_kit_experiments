<!-- <h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p> -->
<script lang="typescript">
	let count = 0;

</script>

<h1 on:click={() => ++count}>{count}</h1>

<style></style>
