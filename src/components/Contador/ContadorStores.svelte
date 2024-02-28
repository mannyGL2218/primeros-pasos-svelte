<script>
	import BtnResetStores from './BtnResetStores.svelte';
	import BtnIncrementarStores from './BtnIncrementarStores.svelte';
    import { conteo } from '../../lib/Contador/stores.js'
	import BtnDecrementarStores from './BtnDecrementarStores.svelte';
    //let valor_cuenta = 0;
    /* El error es que si bien me suscribo al evento, nunca desuscribo, para arreglarlo se utiliza $ directamente
    conteo.subscribe( (value) => {
        valor_cuenta = value;
    } );*/
    //<h3>Contador store: {valor_cuenta}</h3>
</script>

<section>
    <h3>Contador store: {$conteo}</h3>
    <div class="input-group btn-group">
        <BtnIncrementarStores />
        <BtnDecrementarStores />
        <BtnResetStores />
    </div>
</section>

<style>
    section{
        background-color: white;
        width: fit-content;
        padding: 15px;
        border-radius: 10px;
    }

</style>