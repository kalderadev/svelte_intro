<script lang="ts">
	import Chart from '$lib/Chart.svelte';
	import Temperature from '$lib/Temperature.svelte';
</script>

<svelte:head>
	<title>svelte is great</title>
</svelte:head>


<section>
	<h2 class="text-9xl	text-zinc-500 mb-20">
		Climate in Germany
	</h2>

	

	<div class="grid grid-cols-2 gap-4">
		<div class="w-full h-12"><Chart /></div>
		<div class="w-full h-12"><Temperature /></div>
	</div>
	

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
