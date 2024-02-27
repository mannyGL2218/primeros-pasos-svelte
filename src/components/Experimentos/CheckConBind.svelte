<script>
	let checkInterfaz = false;
</script>

<section>
    <label>
        <input type="checkbox" bind:checked={checkInterfaz} />
        Click para acceder
    </label>
    
    {#if checkInterfaz}
        <p>Tienes acceso</p>
    {:else}
        <p>No tienes acceso</p>
    {/if}
    
    <button disabled={!checkInterfaz}>Acceso</button>
</section>

<style>
    section{
        background-color: white;
        width: fit-content;
        margin-top: 20px;
        padding: 20px;
        border-radius: 10px;
    }
</style>