<template>
    <div class="skill">
        <SkillItem name="HTML5" icon='html5' style="color: #fe6703;" />
        <SkillItem name="CSS3" icon='css3' style="color: #1d59be;" />
        <SkillItem name="Vue/Nuxt" icon='vuejs' style="color: #00974b;" />
        <SkillItem name="Rails6" icon='sketch' style="color: #e61313;" />
        <SkillItem name="Docker" icon='docker' style="color: #00acff;" />
        <SkillItem name="AWS" icon='aws' style="color: #faa20e;" />
        <SkillItem name="Git" icon='git' style="color: #ff4600;" />
    </div>
</template>

<script>
import SkillItem from '../components/SkillItem'

export default {
    components: {
        SkillItem,
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