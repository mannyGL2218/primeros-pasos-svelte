<script>
    
</script>

<div>
    <nav>
        <label>MannyGL</label>
        <div></div>
        <a href="/">Home</a>
        <a href="/Contador">Contador</a>
        <a href="/Bootstrap">Bootstrap</a>
    </nav>

    <slot>contenido</slot>

    
</div>

<style>
    nav{
        background-color: blue;
        display: flex;

        padding-top: 10px;
        padding-bottom: 15px;
        
        color: white;
        font-weight: bold;
    }
    label{
        margin-left: 20px;
    }
    div{
        margin-left: auto;
    }
    a{
        color: white;
        margin-left: 20px;
        margin-right: 20px;
        font-weight: bold;
    }
    a:hover{
        color: red;
    }
</style>