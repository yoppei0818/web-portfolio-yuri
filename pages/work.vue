<template>
    <div class="work">
        <WorkItem 
            link="https://github.com/yoppei0818/anime-memo-app.git"
            src="images/アニメ図鑑.png"
            title="アニメ図鑑"
            lang="HTML/SCSS/Vue/Rails6/Heroku"
        />
        <WorkItem 
            link="https://github.com/yoppei0818/oz_website.git"
            src="images/釧路公立大学ストリートダンスサークルOZ.jpg"
            title="釧路公立大学　ストリートダンスサークルOZ　webサイト"
            lang="HTML/CSS/JavaScript"
        />
        <WorkItem 
            link="https://github.com/yoppei0818/weather-api-app.git"
            src="images/天気アプリ.png"
            title="天気アプリ"
            lang="HTML/SCSS/Vue/Heroku"
        />
    </div>
</template>

<script>
import WorkItem from "../components/WorkItem"

export default {
    components: {
        WorkItem,
    }
}
</script>

<style lang="scss" scoped>
.work {
    @include basePage;
    margin-top: 100px;
}
</style>