<template>
    <div class="skill-item">
        <font-awesome-icon class="icon" :icon="['fab', icon]" :style="style" />
        <p>{{ name }}</p>
    </div>
</template>

<script>
export default {
    props:['name', 'icon', 'style']
}
</script>

<style lang="scss" scoped>
.skill-item {
    width: 25%;
    background-color: #fff;
    border: 2px solid rgba(0,0,0,.8);
    border-radius: 15px;
    margin: 15px;
    padding: 30px 15px;
    text-align: center;
    
    .icon {
        font-size: 45px;
    }

    p {
        font-weight: 400;
        font-size: 20px;
        margin-top: 5px;
    }
}

</style>

