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
                {id: 1, img: '', text: 'HTML/CSS'},
                {id: 2, img: '', text: 'JavaScript'},
                {id: 3, img: '', text: 'React'},
                {id: 4, img: '', text: 'Vue'},
                {id: 5, img: '', text: 'Node.js'},
                {id: 6, img: '', text: 'Webpack'},
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
}
</style>