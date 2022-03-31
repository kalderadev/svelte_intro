<script>
	import Temperature from '$lib/Temperature.svelte';
</script>

<section>
	<h2 class="text-9xl	text-zinc-500 mb-20">
		Climate in Germany
	</h2>
	<Temperature />

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
