<template>
  <div class="high_part">
    <div class="container">
      <HeaderPage/>
      <div class="high_layout">
        <ShortDescription />
        <HighDecoration />
      </div>
    </div>

  </div>
</template>

<script>
import HeaderPage from './components/Header.vue'
import ShortDescription from './components/ShortDescription.vue'
import HighDecoration from './components/HighDecoration.vue'

export default {
  name: 'App',
  components: {
    HeaderPage,
    ShortDescription,
    HighDecoration
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
</style>
