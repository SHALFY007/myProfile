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
    <a name="bio"></a>
    <div class="container">
      <SkillCards />
    </div>
</div>
</template>

<script>
import HeaderPage from './components/Header.vue'
import ShortDescription from './components/ShortDescription.vue'
import HighDecoration from './components/HighDecoration.vue'
import SkillCards from './components/SkillCards.vue'

export default {
  name: 'App',
  components: {
    HeaderPage,
    ShortDescription,
    HighDecoration,
    SkillCards
  }
}
</script>

<style>
@font-face {
  font-family: 'Arodora Pro';
  src: url(./fonts/ArodoraPro-Light.otf);
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
  min-height: 115.43rem;
  padding-top: 7rem;
  background: linear-gradient(130.68deg, #414141 0%, #2D2D2D 100.52%);
}
</style>
