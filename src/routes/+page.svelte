<script>
	import Layout from './layout.svelte';
	let contador = 0;

	function incrementar() {
		contador ++;
	}
	function decrementar() {
		contador --;
	}
</script>

<Layout>
	<div class="min-h-screen bg-white">
		<div class="flex justify-center gap-4">
			<button class="px-4 py-2 mt-4 text-white bg-blue-500 rounded" on:click={incrementar}>Incrementar</button>
			<p class="text-5xl pt-4">{contador}</p>
			<button class="px-4 py-2 mt-4 text-white bg-red-500 rounded" on:click={decrementar}>Decrementar</button>
		</div>
	</div>
</Layout>