<template>
    <div class="skill">
        <Item name="HTML5" icon='html5' style="color: #fe6703;" />
        <Item name="CSS3" icon='css3' style="color: #1d59be;" />
        <Item name="Vue/Nuxt" icon='vuejs' style="color: #00974b;" />
        <Item name="Rails6" icon='sketch' style="color: #e61313;" />
        <Item name="Docker" icon='docker' style="color: #00acff;" />
        <Item name="AWS" icon='aws' style="color: #faa20e;" />
        <Item name="Git" icon='git' style="color: #ff4600;" />
    </div>
</template>

<script>
import Item from '../components/Item'

export default {
    components: {
        Item,
    }
}
</script>

<style lang="scss" scoped>
.skill {
    margin: 0 auto;
    width: 85%;
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
    margin-top: 100px;
}
</style>