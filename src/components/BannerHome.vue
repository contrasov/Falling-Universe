<template>
    <div class="banner-app">
        <div class="card-banner">
            <h2>Projeto GameC</h2>
            <p> Após um impulso criativo, surgiu a ideia de desenvolver o início de um pequeno projeto. Com o tempo,
                pretendo aprimorá-lo gradualmente, tornando-o um
                passatempo para mim e para quem quiser acompanhar.</p>
            <button>Saiba Mais</button>
        </div>
    </div>
</template>

<script>
</script>

<style>

.banner-app {
    width: 950px;
    height: 300px;
    background-image: url('@/assets/banner-image.jpg');;
}

.card-banner {
    /* GAMBIARRA */
    margin-left: 652px;
    margin-top: 17px;
    width: 274px;
    height: 266px;
    background-color: #131414;
    text-align: left;
}

h2 {
    color: white;
    font-size: 20px;
    padding-left: 20px;
    padding-top: 16px;
}

p {
    color: white;
    font-size: 15px;
    margin-top: -10px;
    /* GAMBIARRA */
    padding-left: 20px;
    padding-right: 20px;

}

button {
    margin-top: 32px;
    cursor: pointer;
    border: 1px transparent;
    border-radius: 2px;
    padding: 8px 30px;
    font-weight: 700;
    margin-left: 20px;
}

button:hover {
    background-color: #FC4D35;
    color: white;
}
</style>
       