<template>
    <div>
        <h1>{{ message }}</h1>
    </div>
</template>

<script>
export default {
    data: function() {
        return {
        message: "Hello World!"
        }
    }
}
</script>

<style lang="scss" scoped>
h1 {
    color:yellowgreen;
}
</style>