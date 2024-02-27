<script>
	let a = 1;
	let b = 2;
    //* La etiqueta bind actualiza el valor de la variable y
    //* se actualiza la etiqueta cuando actualizas la variable
</script>

<div>
    <center><h4>Etiqueta BIND</h4></center>
    <!--Input A-->
    <label>A
	    <input type="number" bind:value={a} min="0" max="10" />
	    <input type="range" bind:value={a} min="0" max="10" />
    </label><br>
    <!--Input B-->
    <label>B
	    <input type="number" bind:value={b} min="0" max="10" />
	    <input type="range" bind:value={b} min="0" max="10" />
    </label><br>
    <!--Resultado-->
    <center><p>Suma: {a} + {b} = {a + b}</p></center>
</div>
<style>
    div{
        background-color: white;
        width: fit-content;
        padding: 20px;
        border-radius: 10px;
    }
</style>