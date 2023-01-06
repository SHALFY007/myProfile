<template>
<div class="footer">
    <h1 class="footer_header">find me in</h1>
    <div class="social_links">
        <a href="" class="footer_link"> 
            <img class="img" src="/img/telegram.png" alt="telegram"></a>
        <a href="" class="footer_link">  
            <img class="img" src="/img/discord.png" alt=""></a>
        <a href="" class="footer_link">  
            <img class="img" src="/img/github.png" alt=""></a>
    </div>
</div>
</template>

<script>
export default {
    name: 'FooterVue'
}
</script>

<style scoped>
.footer {
    display: flex;
    flex-direction: column;
    align-items: center;
    height: 100%;
}
.footer_header {
    font-family: 'NEXT ART';
    font-style: normal;
    font-weight: 400;
    font-size: 48px;
    line-height: 54px;
    
    color: #FFFFFF;


}
.img {
    width: 50px;
}
</style>