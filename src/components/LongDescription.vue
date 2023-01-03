<template>
    <div class="long_context">
    <div class="long_desciption">
        <div class="long_info">
            <h1 class="long_header">about me</h1>
        <p class="long_txt">Hello again everyone! So, you already know that my name is Vladislav. A little about myself: student, 15 y.o., I love creativity since childhood, I live in Moscow, Russia. Why programming? Everything is elementary - I like it, the profession of the future, thanks to which I can provide myself and fulfill my dream - travel, at the moment I specialize in web design, front-end and back-end development, turnkey websites. Why should you choose me? I approach each order with great responsibility and love, as I want to make a name for myself, exclude plagiarism and negligence, fully study the project, the client and its target audience, work for quality, trying to make an order as quickly and uniquely as possible, taking into account all the edits and wishes.
By trusting me, you will get the maximum return for your project, save your nerves and time.
If you are interested in me , you want to know something more or use my services, then I will provide all my contacts below.</p>
        </div>  
        
    </div>
    <svg class="long_bg_1" width="496" height="496" viewBox="0 0 496 496" fill="none" xmlns="http://www.w3.org/2000/svg">
<g filter="url(#filter0_d_1_64)">
<circle cx="248" cy="244" r="161" stroke="#E2A200" stroke-width="34" shape-rendering="crispEdges"/>
</g>
<defs>
<filter id="filter0_d_1_64" x="0" y="0" width="496" height="496" filterUnits="userSpaceOnUse" color-interpolation-filters="sRGB">
<feFlood flood-opacity="0" result="BackgroundImageFix"/>
<feColorMatrix in="SourceAlpha" type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0" result="hardAlpha"/>
<feOffset dy="4"/>
<feGaussianBlur stdDeviation="35"/>
<feComposite in2="hardAlpha" operator="out"/>
<feColorMatrix type="matrix" values="0 0 0 0 0.886275 0 0 0 0 0.635294 0 0 0 0 0 0 0 0 0.25 0"/>
<feBlend mode="normal" in2="BackgroundImageFix" result="effect1_dropShadow_1_64"/>
<feBlend mode="normal" in="SourceGraphic" in2="effect1_dropShadow_1_64" result="shape"/>
</filter>
</defs>
</svg>
<svg class="long_bg_2" width="932" height="932" viewBox="0 0 932 932" fill="none" xmlns="http://www.w3.org/2000/svg">
<g filter="url(#filter0_d_1_62)">
<circle cx="466" cy="462" r="351.5" stroke="#E4E4E4" stroke-width="89" shape-rendering="crispEdges"/>
</g>
<defs>
<filter id="filter0_d_1_62" x="0" y="0" width="932" height="932" filterUnits="userSpaceOnUse" color-interpolation-filters="sRGB">
<feFlood flood-opacity="0" result="BackgroundImageFix"/>
<feColorMatrix in="SourceAlpha" type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0" result="hardAlpha"/>
<feOffset dy="4"/>
<feGaussianBlur stdDeviation="35"/>
<feComposite in2="hardAlpha" operator="out"/>
<feColorMatrix type="matrix" values="0 0 0 0 1 0 0 0 0 1 0 0 0 0 1 0 0 0 0.25 0"/>
<feBlend mode="normal" in2="BackgroundImageFix" result="effect1_dropShadow_1_62"/>
<feBlend mode="normal" in="SourceGraphic" in2="effect1_dropShadow_1_62" result="shape"/>
</filter>
</defs>
</svg>
<svg class="long_bg_3" width="626" height="626" viewBox="0 0 626 626" fill="none" xmlns="http://www.w3.org/2000/svg">
<g filter="url(#filter0_d_1_63)">
<circle cx="313" cy="309" r="215.5" stroke="#00C4F0" stroke-width="55" shape-rendering="crispEdges"/>
</g>
<defs>
<filter id="filter0_d_1_63" x="0" y="0" width="626" height="626" filterUnits="userSpaceOnUse" color-interpolation-filters="sRGB">
<feFlood flood-opacity="0" result="BackgroundImageFix"/>
<feColorMatrix in="SourceAlpha" type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0" result="hardAlpha"/>
<feOffset dy="4"/>
<feGaussianBlur stdDeviation="35"/>
<feComposite in2="hardAlpha" operator="out"/>
<feColorMatrix type="matrix" values="0 0 0 0 0 0 0 0 0 0.756863 0 0 0 0 0.92549 0 0 0 0.25 0"/>
<feBlend mode="normal" in2="BackgroundImageFix" result="effect1_dropShadow_1_63"/>
<feBlend mode="normal" in="SourceGraphic" in2="effect1_dropShadow_1_63" result="shape"/>
</filter>
</defs>
</svg>
</div>
</template>

<script>
export default {
    name: 'LongDescription'
}
</script>

<style scoped>
.long_bg_1 {
    position: absolute;
    top: -136px;
    left: 542px;
}
.long_bg_2 {
    position: absolute;
    top: -42px;
    left: -36px;
}
.long_bg_3 {
    position: absolute;
    top: 392px;
left: 427px;
}
.long_context {
    position: relative;
}
.long_desciption {
    height: 822px;
    width: 496px;
    margin: 0 auto;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    background: #2C2C2C;
    border-radius: 14px;
    position: absolute;
    left: 0;
    right: 0;
    z-index: 3;
}
.long_header {
    font-family: 'NEXT ART';
    font-style: normal;
    font-weight: 400;
    font-size: 48px;
    line-height: 54px;
    position: absolute;
    top: -27px;
    left: 33px;

    color: #E4E4E4;


}
.long_txt {
    max-width: 370px;
    font-family: 'Arodora Pro';
    font-style: normal;
    font-weight: 300;
    font-size: 20px;
    line-height: 24px;
    display: flex;
    align-items: center;
    letter-spacing: 0.01em;

color: #FFFFFF;
}
</style>