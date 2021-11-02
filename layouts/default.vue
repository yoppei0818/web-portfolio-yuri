<template>
    <div class="app">
        <div class="header">
            <h1>Yuri Yohei.</h1>
            <Navigation route="/" name="HOME" icon="home" />
            <Navigation route="/skill" name="SKILL" icon="code" />
            <Navigation route="/work" name="WORK" icon="gamepad" />
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
.app {
    background-color: rgba(245, 245, 245, 0.836);
    height: 100vh; 

    .header {
        padding-top: 20px;
        margin: 0 auto;
        width: 600px;
        display: flex;
        justify-content: space-around;
        margin-bottom: 25px;

        h1 {
            font-weight: 300;
            font-size: 40px;
            font-family: 'Ubuntu', sans-serif;
            padding-top: 25px;
        }
    }
}
</style>