<script>
    import { count } from '$lib';
</script>

<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>

<h1>{$count}</h1>
<button on:click={() => count.update(n => n+1)}>
    Increment
</button>
