<template>
    <div class="work-item">
        <a :href="link">
            <img :src="require(`@/assets/${src}`)" :alt="title">
            <p class="title">{{ title }}</p>
            <p class="lang">Tool：{{ lang }}</p>
        </a>
    </div>
</template>

<script>
export default {
    props:['link', 'src', 'title', 'lang'],
}
</script>

<style lang="scss" scoped>
.work-item {
    width: 25%;
    background-color: #fff;
    border: 1px solid $LightBlack;
    border-radius: 15px;
    margin: 15px;
    padding: 30px 15px;
    text-align: center;
    transition: 0.3s;
    cursor: pointer;

    &:hover {
        box-shadow: 0 3px 5px black;
        transform: translate(0, -3px);
    }

    a {
        text-decoration: none;

        img {
            margin: 0 auto;
            width: 90%;
            box-shadow: 1px 1px 10px $LightBlack;
            
        }
        
        .title {
            color: $LightBlack;
            font-size: 18px;
            font-weight: 600;
            margin-top: 20px;
        }

        .lang {
            color: $LightBlack;
            font-size: 12px;
            font-weight: 600;
            margin-top: 20px;
        }
    }
}
</style>