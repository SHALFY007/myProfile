<template>
<div class="footer">
    <h1 class="footer_header">find me in</h1>
    <div class="social_links">
        <a v-for="i in links" :href="i.path" :key="i.id">
            <img class="img" :src="i.img" :alt="i.title">
        </a>
    </div>
</div>
</template>

<script>
export default {
    name: 'FooterVue',
    data() {
        return {
            links: [
        {id: 1, title: "Telegram", img: '/img/telegram.png', path: 'https://t.me/vlshalf'},
        {id: 2, title: "Discord", img: '/img/discord.png', path : ''},
        {id: 3, title: "GitHub", img: '/img/github.png', path: 'https://github.com/SHALFY007'},
    ]
        }
    }
    
}
</script>

<style scoped>
.footer {
    display: flex;
    flex-direction: column;
    min-height: 239px;
    justify-content: space-evenly;
}
.footer_header {
    font-family: 'NEXT ART';
    font-style: normal;
    font-weight: 400;
    font-size: 48px;
    line-height: 54px;
    
    color: #FFFFFF;


}
.social_links {
    width: 100%;
    display: flex;
    justify-content: space-between;
}
.img {
    width: 50px;
}
</style>