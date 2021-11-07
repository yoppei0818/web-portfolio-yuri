<template>
    <div class="skill-item">
        <font-awesome-icon 
            class="icon" 
            :icon="['fab', icon]" 
            :style="`color: ${ styles };`" 
        />
        <p>{{ name }}</p>
    </div>
</template>

<script>
export default {
    props:['name', 'icon', 'styles']
}
</script>

<style lang="scss" scoped>
.skill-item {
    width: 25%;
    background-color: #fff;
    border: 2px solid $LightBlack;
    border-radius: 15px;
    margin: 15px;
    padding: 30px 15px;
    text-align: center;

    @include sp {
        width: 35%;
        border: 1px solid $LightBlack;
    }
    
    .icon {
        font-size: 45px;

        @include sp {
            font-size: 35px;
        }
    }

    p {
        font-weight: 400;
        font-size: 20px;
        margin-top: 5px;

        @include sp {
            font-size: 18px;
        }
    }
}

</style>

