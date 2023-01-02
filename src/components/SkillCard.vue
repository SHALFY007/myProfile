<template>
    <div class="skill_card">
        <img :src="type.img" alt="logo" style="max-width: 110px; min-height: 110px;">
        <p class="skill_card_txt">{{ type.text }}</p>
    </div>
</template>

<script>
export default {
    name: "SkillCard",
    props: {
        type: Object
    }
}
</script>

<style scoped>
.skill_card {
    width: 270px;
    height: 270px;
    margin-bottom: 30px;
    background: #2A2A2A;
    box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.47);
    border-radius: 29px;
    align-items: center;
    display: flex;
    flex-direction: column;
    justify-content: inherit;
}
.skill_card_txt {
    font-weight: 300;
    font-style: normal;
    font-size: 24px;
    line-height: 29px;
    /* text */
    color: #E4E4E4;


}
</style>