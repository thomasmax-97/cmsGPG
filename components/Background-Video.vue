<template>
    <div class="gpg-video">
        <video
            class="w-full fixed gpg-video"
            playsinline
            autoplay
            loop
            muted>
            <source
                src="~/assets/video/gpg-gaming.mp4"
                type="video/mp4">
        </video>
    </div>
</template>

<script>

</script>

<style>
.gpg-video {
    position: fixed;
    margin-top: -20px;
    z-index: -1;
    width: 100%;
    height: auto;
}
</style>