<script>
	import { conteo } from './../../lib/Contador/stores.js';

	function reset() {
		conteo.set(0);
	}
</script>

<button on:click={reset} class="btn btn-info">
	reset
</button>