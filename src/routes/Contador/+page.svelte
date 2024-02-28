<script>
	import ContadorStores from './../../components/Contador/ContadorStores.svelte';
	import Contador from './../../components/Contador/Contador.svelte';
	import Titulo from './../../components/Generales/Titulo.svelte';
</script>

<main>
    <Titulo Titulo="Contador"/>

    <div id="contador_store">
        <ContadorStores />
    </div>

    <center>
        <Contador valorInicial={10} limite={20} />
        <Contador valorInicial={5}/>
        <Contador />
    </center>

</main>

<style>
    #contador_store{
        display: flex;
        justify-content: center;   
    }
</style>