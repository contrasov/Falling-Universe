<template>
    <div class="feed-container">
        <div class="post-list">
            <div class="feed-post">
            <img id="post-photo" src="@/assets/post-img.svg" alt="photo-feed">
            <div class="text-content">
                <h2 class="title-post">Pequeno Projeto</h2>
                <p class="text-post">Início de um pequeno projeto com vue.js e criatividade para um joguinho.</p>
                <div class="date-info">
                    <img id="calendar" src="@/assets/calendar.svg" alt="calendar-icon">
                    <p id="date">3 Fevereiro, 2024</p>
                </div>
            </div>
        </div>
            <div class="feed-post">
            <img id="post-photo" src="@/assets/post-img.svg" alt="photo-feed">
            <div class="text-content">
                <h2 class="title-post">A ideia das atualizações</h2>
                <p class="text-post">Aqui vou falar como vou prosseguir e como será o desenvolvimento do projeto.</p>
                <div class="date-info">
                    <img id="calendar" src="@/assets/calendar.svg" alt="calendar-icon">
                    <p id="date">10 Janeiro, 2024</p>
                </div>
            </div>
        </div>
        </div>
        <div class="social-media">
            <a href="https://www.twitch.tv/contrasov" target="_blank">
                <img id="twitch" src="@/assets/twitch.svg" alt="twitch-channel">
            </a>
            <a href="https://twitter.com/sleep_ze" target="_blank">
                <img id="x" src="@/assets/x.svg" alt="x">
            </a>
            <a href="https://www.linkedin.com/in/alvarosantosuidev/" target="_blank">
                <img id="linkedin" src="@/assets/linkedin.svg" alt="linkedin">
            </a>
        </div>
    </div>
</template>

<script>

</script>

<style>

.feed-container {
    max-width: 950px;
    padding-bottom: 17px;
    background-color: #1F222B;
    display: flex;
}

.social-media {
    display: inline-flex;
    flex-direction: column;
    gap: 6px;
    margin-top: 17px;
    margin-right: 24px;
}

#twitch, #x, #linkedin {
    cursor: pointer;
}

.feed-post {
    cursor: pointer;
    display: inline-flex;
    background-color: #2A2E37;
    margin-top: 17px;
    margin-left: 24px;
    padding: 10px;
    float: left;
    /*sabia disso nao*/
}


.feed-post:hover {
    background-color: #FC4D35;
}

.text-content {
    display: flex;
    flex-direction: column;
    text-align: left;
    margin-left: 16px;
    gap: 8px;
}

.title-post {
    display: inline-flex;
    font-size: 20px;
    margin: 0;
    padding: 0;
}

.text-post {
    color: rgba(255, 255, 255, 0.40);
    margin-right: 1000px;
    margin: 0;
    padding: 0;
    max-width: 506px;
    height: 1.5em;
    font-size: 16px;
}


.date-info {
    margin-top: 20px;
    display: flex;
    align-items: center;
    font-weight: 700;
    font-size: 15px;
}

#date {
    padding: 0;
    margin: 0 10px;
}

#calendar {
    max-width: 14px;
    height: auto;
}
</style>
