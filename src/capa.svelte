<script>

import Caixadeicones from "./Caixadeicones.svelte";

</script>

<div class="fundo">
    <div class="centro">
        <img src="./img\IMG_20210221_170111_898.jpg" alt="foto lincoln" class="foto">
        <h1 class="titulo">lincoln Ramos</h1>
        <h2 class="descricao"> estutante de analise e desenvolvimento de sistemas</h2>
        <Caixadeicones />
    </div>
</div>

<style>
    .fundo{
        width: 100%;
        min-height: 100vh;
        background-color: darkblue;
    }
    .centro{
        color: white;
        text-align: center;
        position: absolute;
        top:50%;
        left:50%;
        transform: translate(-50%, -50%);

    }
    .foto{
        border-radius: 50%;
        width: 250px;
    }
    .titulo{
        font-size: 40px;

    }
    .descricao{
        font-size: 25px;
    }
</style>