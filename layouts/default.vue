<template>
    <div class="app">
        <div class="header">
            <Navigation route="/" name="HOME" />
            <Navigation route="/skill" name="SKILL" />
            <Navigation route="/work" name="WORK" />
        </div>
        <Nuxt />
    </div>
</template>

<script>
import Navigation from '../components/Navigation'

export default {
    components: {
        Navigation,
    }
}
</script>

<style lang="scss" scoped>
.header {
    display: flex;
    background-color: burlywood;
}
</style>