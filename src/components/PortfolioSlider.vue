<template>
    <div class="portfolio_slider">

        <div class="slider_screen">
            <swiper :modules="modules" :pagination="{ clickable: true }" :autoplay="{ delay: 5000, disableOnInteraction: false} ">
                <!-- <swiper-slide>
        <img src="/img/js.png" alt="">
    </swiper-slide>
    <swiper-slide><img src="/img/vue.png" alt=""></swiper-slide>
    <swiper-slide>Slide 3</swiper-slide> -->
    <swiper-slide v-for="i in sliders" :key="i.id">
        <OnePortfolioSlide :slideInfo="i"/>
    </swiper-slide>
            </swiper>
        </div>
    </div>
</template>

<script>
import  { Pagination, Autoplay } from 'swiper'
  import { Swiper, SwiperSlide } from 'vue-awesome-swiper'
  // import swiper module styles
  import 'swiper/css'
  import 'swiper/css/pagination'
import OnePortfolioSlide from './OnePortfolioSlide.vue'
  // more module style...

export default {
    name: 'PortfolioSlider',
    components: {
    Swiper,
    SwiperSlide,
    OnePortfolioSlide
},
    data() {
        return {
            sliders : [
                {
                    id:1, img: '/img/slider_1.png', description: 'Online Shop'
                },
                {
                    id:2, img: '/img/slider_2.png', description: 'Pet project'
                },
                {
                    id:3, img: '/img/slider_3.png', description: 'Costs manager on Vue'
                },
                {
                    id:4, img: '/img/js.png', description: 'Messanger on React with using Firebase'
                },
                {
                    id:5, img: '/img/slider_5.png', description: 'Taked part in creating Keyboard Trainer on React'
                },
                {
                    id:6, img: '/img/slider_6.png', description: 'Profile on Vue'
                }
            ]
        }
    },
    setup() {
      return {
        modules: [Pagination, Autoplay]
      }
    }
}
</script>

<style scoped>
.portfolio_slider {
    margin-top: 50px;
    display: flex;
    flex-direction: column;
    align-items: center;
}
.slider_screen {
    width: 970px;
    height: 600px;
    
    /* Gray2 */
    background: linear-gradient(130.68deg, #414141 0%, #2D2D2D 100.52%);
    box-shadow: 0px 4px 15px rgba(27, 27, 27, 0.28);
    border-radius: 29px;
}
.swiper {
    height: 100%;
}
@media (max-width: 1199px) {
    .slider_screen {
        width: 797px;
    }
}
</style>