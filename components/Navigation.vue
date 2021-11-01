<template>
    <div class="header-item">
        <!-- <font-awesome-icon icon="home" /> -->
        <nuxt-link v-bind:to="route">{{ name }}</nuxt-link>
    </div>
</template>

<script>
export default {
    props: ['route', 'name']
}
</script>

<style lang="scss" scoped>
    .header-item {
        background-color: cadetblue;
    }
</style>