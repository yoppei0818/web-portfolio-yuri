<template>
    <div class="skill">
        <SkillItem name="HTML5" icon='html5' styles="#fe6703" />
        <SkillItem name="CSS3" icon='css3' styles="#1d59be" />
        <SkillItem name="Vue/Nuxt" icon='vuejs' styles="#00974b" />
        <SkillItem name="Rails6" icon='sketch' styles="#e61313" />
        <SkillItem name="Docker" icon='docker' styles="#00acff" />
        <SkillItem name="AWS" icon='aws' styles="#faa20e" />
        <SkillItem name="Git" icon='git' styles="#ff4600" />
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
    @include basePage;
    margin-top: 100px;

    @include sp {
        margin-top: 25px;
    }
}
</style>