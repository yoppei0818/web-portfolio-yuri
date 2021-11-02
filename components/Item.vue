<template>
    <div class="item">
        <font-awesome-icon class="icon" v-bind:icon="['fab', icon]" />
        <h1>{{ name }}</h1>
    </div>
</template>

<script>
export default {
    props:['name', 'icon']
}
</script>

<style lang="scss" scoped>
h1 {
    color: olive;
}

.icon {
    color:orangered;
}
</style>

