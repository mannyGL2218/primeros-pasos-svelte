<script>
import Carta from "../../components/Bootstrap/Carta.svelte";
import Titulo from "../../components/Generales/Titulo.svelte";
let pan = [1,2,3,4,5,6,7,8]
</script>

<main class="container">
    <Titulo Titulo="Prueba Bootstrap" />

    <div class="album py-5">
        <div class="container">
            <div class="row">

                {#each pan as carta}
                    <Carta Descripcion="Bocchi" />
                {/each}
            
            </div>
        </div>
    </div>
</main>

<style>
    main{
        background-color: lightseagreen;
        border-radius: 30px;
        margin-bottom: 100px;
        margin-top: 40px;
        padding-top: 10px;
    }
</style>