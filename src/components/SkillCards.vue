<template>
    <div class="skill_cards">
            <SkillCard v-for="i in skills" :key="i.id" :type="i" />
    </div>
</template>

<script>
import SkillCard from './SkillCard.vue'
export default {
    name: 'SkillCards',
    components: {
        SkillCard
    },
    data() {
        return {
            skills: [
                {id: 1, img: './img/html.png', text: 'HTML/CSS'},
                {id: 2, img: './img/js.png', text: 'JavaScript'},
                {id: 3, img: './img/react.png', text: 'React'},
                {id: 4, img: './img/vue.png', text: 'Vue'},
                {id: 5, img: './img/node.png', text: 'Node.js'},
                {id: 6, img: './img/ts.png', text: 'TypeScript'},
                {id: 7, img: './img/git.png', text: 'Git'},
            ]
        }
    }
}
</script>

<style scoped>
.skill_cards {
    display: flex;
    justify-content: space-around;
    flex-wrap: wrap;
    margin-bottom: 9.56rem;
}
</style>