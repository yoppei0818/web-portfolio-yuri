<template>
    <div class="skill">
        <Item name="HTML5" icon='html5' />
        <Item name="CSS3" icon='css3' />
        <Item name="Vue/Nuxt" icon='vuejs' />
        <Item name="Rails6" icon='sketch' />
        <Item name="Docker" icon='docker' />
        <Item name="AWS" icon='aws' />
        <Item name="Git" icon='git' />
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
    width: 85%;
}
</style>