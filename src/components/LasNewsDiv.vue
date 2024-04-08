<template>
    <div class="title-news">
        <div id="left-div"></div>
        <h2 id="title-news2">Últimas<span id="colorized-text">Notícias</span></h2>
        <div id="right-div"></div>
    </div>
</template>

<script> 

</script>

<style>
.title-news {
    display: flex;
    align-items: center;
    gap: 16px;
}

#title-news2 {
    padding: 0px;
}

#colorized-text {
    color: #FC4D35;
    margin-left: 6px;
    margin-right: 16px;
}


#left-div {
    background-color: #101010;
    width: 80px;
    height: 5px;
    margin-left: 0px; /*ngm viu..*/
} 

#right-div {
    background-color: #101010;
    width: 670px;
    height: 5px;
}

</style>
 

