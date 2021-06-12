<script context="module">
    // console.log($lib)

import  '$lib'
	export function load() {
		return { props: 'bruno' };
	}

</script>

<!-- <h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p> -->
<script lang="typescript">
	let count = 0;

// import lib from '$lib'
</script>

<svelte:head>
	<title>{count}</title>
</svelte:head>

<h1 on:click={() => ++count}>{count}</h1>
<!-- <h2>{JSON.stringify(props)}</h2> -->

<h3>{lib}</h3>

<!-- <svg viewBox="0 0 10 10" xmlns="http://www.w3.org/2000/svg">
    <rect width="10" height="10">
      <animate attributeName="rx" values="0;5;0" dur="10s" repeatCount="indefinite" />
    </rect>
  </svg> -->
<style>
	h1 {
		user-select: none;
		color: yellowgreen;
	}

</style>
