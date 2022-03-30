<script context="module" lang="ts">
	export const prerender = true;
</script>

<script lang="ts">
	import Counter from '$lib/Counter.svelte';
	import Temperature from '$lib/Temperature.svelte';
</script>

<svelte:head>
	<title>svelte is great</title>
</svelte:head>

<section>
	<h2 class="text-9xl	text-zinc-500 mb-20">
		Climate in Germany
	</h2>
	<Temperature />

	<!-- <div class="grid gap-4 grid-cols-2">
		<div class="w-1/2 bg-gray-400 h-12"><Counter /></div>
		<div class="w-1/2 bg-gray-500 h-12"><Counter /></div>
	</div> -->

</section>

<style>
	section {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		flex: 1;
	}

	h2 {
		width: 120%;
	}

</style>
