<script>
    import { conteo } from '../../lib/Contador/stores.js'

	function decrement() {
		conteo.update((n) => n - 1);
	}
</script>

<button on:click={decrement} class="btn btn-danger">
	-
</button>
