<script>
    export let valorInicial = 0;
    export let limite = 0;
    let contador = valorInicial;

    $:if(limite != 0){
        if(contador > limite){
            contador = limite;
        }
    }

    const sumar = () => {
        contador++;
    }

    const reset = () => {
        contador = valorInicial;
    }
</script>

<section>
    <h2>Contador = {contador}</h2>
    <button on:click={sumar} type="button">Sumar</button>
    <button on:click={reset} type="button">Reset</button>
</section>

<style>
    section{
        background-color: lightblue;
        width: fit-content;
        padding: 10px;
        border-radius: 20px;
        margin-top: 10px;
    }
</style>