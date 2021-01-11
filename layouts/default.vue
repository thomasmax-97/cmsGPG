<template>
    <div class="flex flex-col h-screen justify-between">
        <BackGroundVideo/>
        <Navigation/>
        <Nuxt/>
        <Footer/>
    </div>
</template>

<script>
import Navigation from '~/components/Navigation'
import BackGroundVideo from '~/components/Background-Video'
import Footer from '~/components/Footer'

export default {
    components: {
        Navigation,
        BackGroundVideo,
        Footer
    },
}
</script>

<style>

</style>
