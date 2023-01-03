<template>
  <div class="high_part">
    <div class="container">
      <HeaderPage/>
      <div class="high_layout" name="home">
        <ShortDescription />
        <HighDecoration />
      </div>
    </div>

  </div>
  <div class="main_layout">
    
    <div class="container">
      <SkillCards />
      <a name="bio"></a>
      <LongDescription />
    </div>
</div>
  <div class="portfolio_layout">
    <a name="portfolio"></a>
    <h1 class="portfolio_header">Portfolio</h1>
    <PortfolioSlider />
  </div>
</template>

<script>
import HeaderPage from './components/Header.vue'
import ShortDescription from './components/ShortDescription.vue'
import HighDecoration from './components/HighDecoration.vue'
import SkillCards from './components/SkillCards.vue'
import LongDescription from './components/LongDescription.vue'
import PortfolioSlider from './components/PortfolioSlider.vue'

export default {
  name: 'App',
  components: {
    HeaderPage,
    ShortDescription,
    HighDecoration,
    SkillCards,
    LongDescription,
    PortfolioSlider
}
}
</script>

<style>
@font-face {
  font-family: 'Arodora Pro';
  src: url(./fonts/ArodoraPro-Light.otf);
}
@font-face {
    font-family: 'NEXT ART';
    src: url(./fonts/NEXT_ART_Bold.otf);
}
* {
  margin: 0;
  padding: 0;
  font-family: 'Arodora Pro';
  box-sizing: border-box;
}
#app {
  text-align: center;
}
.high_part {
  height: 47.5rem;
  background: #2C2C2C;
  padding-top: 26px;
}
.container {
  width: 1200px;
  margin: 0 auto;
}
.high_layout {
  display: flex;
}
.main_layout {
  overflow: hidden;
  min-height: 115.43rem;
  padding-top: 7rem;
  background: linear-gradient(130.68deg, #414141 0%, #2D2D2D 100.52%);
}
.portfolio_layout {
  min-height: 59.625rem;
  width: 100%;
  background-color: #262626;
  padding-top: 100px;
  display: flex;
  flex-direction: column;
  justify-content: center;
}
.portfolio_header {

  font-family: 'NEXT ART';
  font-style: normal;
  font-weight: 400;
  font-size: 48px;
  line-height: 54px;
  
  color: #FFFFFF;


}
@keyframes apear {
  0% {opacity: 0;}
  100% {opacity: 1;}
}
</style>
