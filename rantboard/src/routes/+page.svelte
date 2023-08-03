<svelte:head>
    <title>RantBoard</title>
</svelte:head>

<script>
	import { fade, fly } from "svelte/transition";

    let name = '';
    let surprise = false;
    fade
</script>

<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>
<input type="text" bind:value={name}/>
<p>{name}</p>
<button on:click={() => surprise = !surprise}>
    Toggle surprise
</button>
{#if surprise}
    <p in:fly={{y:200, duration:3000}} out:fade>🎉 Surprise! 🎉</p>
{/if}

