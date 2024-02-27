<script>
    export let Descripcion = "Descripcion";
    export let ImagenSrc = `https://i.postimg.cc/JtVRFZkW/Ojos-de-Bocchi.png`;

</script>

<div class="col-lg-4 col-md-6 col-sm-12 col-12">
    <div class="card mb-4 box-shadow">
        <img class="card-img-top" alt="Miniatura [100%x225]" style="height: 225px; width: 100%; display: block;" src={ImagenSrc} loading="lazy" data-holder-rendered="true">
        
        <div class="card-body">
            <p class="card-text">{Descripcion}</p>

            <div class="d-flex justify-content-between align-items-center">
                <div class="input-group btn-group">
                    <button type="button" class="btn btn-sm btn-outline-danger">View</button>
                    <button type="button" class="btn btn-sm btn-outline-success">Edit</button>
                </div>
            </div>
        </div>
    </div>
</div>

<style>

</style>