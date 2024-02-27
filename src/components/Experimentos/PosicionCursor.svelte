<script lang="ts">
    let coordenadas = { x: 0, y: 0 };

    const movimientoMouse = (  {clientX, clientY} : MouseEvent ) => {
        coordenadas.x = clientX;
        coordenadas.y = clientY;
    }
</script>

<div on:pointermove = { movimientoMouse } >
    <span>El cursor esta en X:{coordenadas.x} , Y:{coordenadas.y}</span>
</div>

<style>
    div {
		position: fixed;
		left: 0;
		top: 0;
		width: 100%;
		height: 100%;
        color: white;
		padding-left: 1em;
	}
    span{
        position: fixed;
        padding: 10px;
        border-radius: 10px;
        background-color: steelblue;
        top: 93%;
    }
</style>