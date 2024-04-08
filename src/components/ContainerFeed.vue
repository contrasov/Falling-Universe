<template>
    <div class="feed-container">
        <div class="feed-post">
            <PostFeed></PostFeed>
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
import PostFeed from '@/components/PostFeed.vue'

export default {
    components: {
        PostFeed
    }
}

</script>

<style>

.feed-container {
    max-width: 950px;
    background-color: #131414;
    display: flex;
}

.social-media {
    display: inline-flex;
    flex-direction: column;
    gap: 6px;
    margin-top: 17px;
    margin-right: 24px;
    margin-left: 16px;
}

#twitch, #x, #linkedin {
    cursor: pointer;
}
</style>
