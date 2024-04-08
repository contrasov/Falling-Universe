<template>
    <div class="ordem">
        <div class="post">
            <figure id="cover-post">
                <img src="@/assets/post-img.svg" alt="cover do post">
            </figure>
            <div class="informations-post">
                <h2 id="title">Titulo Aleatorio #1</h2>
                <!-- 89 caracteres maximo (talvez) -->
                <p id="subtitle">descrição do post aleatoriamente, esse texto é so para marcar o espaço, oi e talvek o
                    krl</p>
            </div>
        </div>
        <div class="post2"> 
            <figure id="cover-post">
                <img src="@/assets/post-img.svg" alt="cover do post">
            </figure>
            <div class="informations-post">
                <h2 id="title">Titulo Aleatorio #2</h2>
                <!-- 89 caracteres maximo (talvez) -->
                <p id="subtitle">descrição do post aleatoriamente, esse texto é so para marcar o espaço, oi e talvek o
                    krl</p>
            </div>
        </div>
    </div>
</template>

<script>

</script>

<style>
#cover-post {
    margin: 0px;
}

.post {
    cursor: pointer;
    gap: 12px;
    display: inline-flex;
    padding: 0%;
    margin: 17px 24px 12px 24px;
    padding: 8px;
    background-color: #0F0F0F;

}

.post2 {
    cursor: pointer;
    gap: 12px;
    display: inline-flex;
    padding: 0%;
    margin: 0px 24px 24px 24px;
    padding: 8px;
    background-color: #0F0F0F;

}

.post:hover {
    background-color: #1B1B1B;
}

.post2:hover {
    background-color: #1B1B1B;
}

#subtitle {
    padding: 0px;
    color: #707070;
}

#title {
    padding: 0px;
    margin-top: 0px;
}

.informations-post {
    text-align: left;
}
</style>