<template>
    <div class="high_description" ref="description">
        <h2 class="description_header_mini">hello</h2>
        <h1 class="description_header">i'm Vlad  Evlashin</h1>
        <p class="description_txt">I've been doing, front-end and back-end development for a year now. Do you need a, site layout, or maybe a turnkey website? Then contact me</p>
        <button class="contact_btn">Contact me</button>
</div>
</template>

<script>
export default {
    name: 'ShortDescription',
}
</script>

<style scoped>
@font-face {
    font-family: 'NEXT ART';
    src: url(../fonts/NEXT_ART_Bold.otf);
}
.high_description {
    max-width: 27.92rem;
    margin-top: 12.93rem;
    height: 377px;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    align-items: flex-start;
    animation: apear 3s forwards;
}
.description_header_mini {
    font-family: 'NEXT ART';
    font-style: normal;
    font-weight: 600;
    font-size: 48px;
    line-height: 54px;
    text-transform: uppercase;
    /* text */
    color: #E4E4E4;
}
.description_header {
    font-family: 'NEXT ART';
    font-style: normal;
    font-weight: 700;
    font-size: 72px;
    text-align: initial;
    line-height: 82px;
    text-transform: uppercase;
    color: #E4E4E4;
}
.description_txt {
    font-style: normal;
font-weight: 300;
font-size: 18px;
line-height: 21px;
    text-align: initial;

/* text */
color: #E4E4E4;
}
.contact_btn {
    width: 200px;
    height: 47px;   
    
    background-color: #E29500 ;
    box-shadow: 0px 2px 13px rgba(226, 158, 0, 0.48);
    border-radius: 6px;
    font-style: normal;
    font-weight: 700;
    font-size: 18px;
    line-height: 20px;
    
    color: #000000;
    font-family: 'NEXT ART';
    transition: all 1s ease;
}
.contact_btn:hover {
    color: #E29500;
    background-color: #fff;
    box-shadow: none;
}
@keyframes apear {
  0% {opacity: 0;}
  100% {opacity: 1;}
}
@media (max-width: 1199px) {
    .high_description {
        max-width: 100%;
        align-items: center;
    }
}

@media (max-width: 764px) {
    .description_header, 
    .description_txt {
        text-align: center;
    }
}
</style>