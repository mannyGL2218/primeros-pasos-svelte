<script>
    import { conteo } from '../../lib/Contador/stores.js'

	function increment() {
		conteo.update((n) => n + 1);
	}
</script>

<button on:click={increment} class="btn btn-success">
	+
</button>