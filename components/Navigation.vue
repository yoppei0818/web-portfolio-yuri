<template>
    <div class="header-item">
        <font-awesome-icon class="icon" :icon="['fas', icon]" />
        <nuxt-link class="link" :to="route">{{ name }}</nuxt-link>
    </div>
</template>

<script>
export default {
    props: ['route', 'name', 'icon']
}
</script>

<style lang="scss" scoped>
    .header-item {
        display: flex;
        flex-direction: column;
        margin: 15px;
        border-bottom: solid 1px $LightBlack;

        &:hover {
            opacity: 0.8;
        }

        .icon {
            font-size: 35px;
            color: $LightBlack;
        }

        .link {
            text-decoration: none;
            color: #000;
            font-size: 12px;
            text-align: center;
            margin-top: 5px;
        }
    }
</style>