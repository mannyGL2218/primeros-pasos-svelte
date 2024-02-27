<script>
	import Contador from './../../components/Contador/Contador.svelte';
	import Titulo from './../../components/Generales/Titulo.svelte';
</script>

<main>
    <Titulo Titulo="Contador"/>

    <center>
        <Contador valorInicial={10} limite={20} />
        <Contador valorInicial={5}/>
        <Contador />
    </center>

</main>

<style>

</style>