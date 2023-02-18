<template>
<div class="portfolio_slide">
    <img :src="slideInfo.img" alt="" class="slider_img">
    <p class="portfolio_description">{{ slideInfo.description }}</p>
</div>
</template>

<script>
export default {
    name: 'OnePortfolioSlide',
    props: {
        slideInfo: Object
    }
}
</script>

<style scoped>
.portfolio_slide {
    /* display: flex; */
    flex-direction: column;
    justify-content: space-between;
    padding-top: 20px;
}
.slider_img {
    max-width: 760px;
    height: 383px;
    border-radius: 20px;
}
.portfolio_description {
    font-family: 'Arodora Pro';
font-style: normal;
font-weight: 300;
font-size: 24px;
line-height: 29px;

/* identical to box height */
align-items: center;

color: #FFFFFF;




}

@media (max-width: 764px) {
    .slider_img {
        max-width: 100%;
        height: auto;
    }
}
</style>