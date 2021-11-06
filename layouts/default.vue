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

    @include sp {
        height: 125vh; 
    }

    .header {
        padding-top: 20px;
        margin: 0 auto;
        width: 42%;
        display: flex;
        justify-content: space-around;
        margin-bottom: 25px;
        // background-color: aqua;

        @include sp {
            width: 80%;
            margin-bottom: 10px;
            padding-top: 10px;
        }

        h1 {
            font-weight: 300;
            font-size: 40px;
            font-family: 'Ubuntu', sans-serif;
            padding-top: 25px;

            @include sp {
                font-size: 20px;
            }
        }
    }
}
</style>