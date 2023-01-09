<template>
    <div class="high_decoration">
        <svg class="high_bg" width="575" height="575" viewBox="0 0 879 880" fill="none" xmlns="http://www.w3.org/2000/svg">
<g filter="url(#filter0_d_1_126)">
<circle cx="439.5" cy="439.972" r="254" stroke="#00C4F0" stroke-width="67" shape-rendering="crispEdges"/>
</g>
<defs>
<filter id="filter0_d_1_126" x="0" y="0.47229" width="879" height="879" filterUnits="userSpaceOnUse" color-interpolation-filters="sRGB">
<feFlood flood-opacity="0" result="BackgroundImageFix"/>
<feColorMatrix in="SourceAlpha" type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0" result="hardAlpha"/>
<feOffset/>
<feGaussianBlur stdDeviation="76"/>
<feComposite in2="hardAlpha" operator="out"/>
<feColorMatrix type="matrix" values="0 0 0 0 0 0 0 0 0 0.768627 0 0 0 0 0.941176 0 0 0 0.42 0"/>
<feBlend mode="normal" in2="BackgroundImageFix" result="effect1_dropShadow_1_126"/>
<feBlend mode="normal" in="SourceGraphic" in2="effect1_dropShadow_1_126" result="shape"/>
</filter>
</defs>
</svg>
    <img src="/img/im.png" class="high_img" alt="photo">
    </div>
</template>

<script>
export default {
    name: 'HighDecoration'
}
</script>

<style scoped>
.high_decoration {
    position: relative;
    margin-top: 7rem;
    margin-left: 11rem;
    animation: apear 3s forwards;
}
.high_bg {
    transform: scale(150%);
}
.high_img {
    position: absolute;
    top: -73px;
    left: 63px;
}
@keyframes apear {
  0% {opacity: 0;}
  100% {opacity: 1;}
}
@media (max-width: 1199px) {
    .high_decoration {
    display: none;
}
}
</style>