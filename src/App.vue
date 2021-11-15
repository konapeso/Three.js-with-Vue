<template lang="pug">
    #app
        the-canvas
</template>

<script>
import TheCanvas from './components/TheCanvas'

export default {
    name: 'App',
    components: {
        TheCanvas,
    },
}
</script>
<style lang="scss" src="./assets/css/app.css"></style>

