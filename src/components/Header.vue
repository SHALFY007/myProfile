<template>
  <div class="header">
    <div class="logo_left"></div>
    <div class="link_right">
      <a href="#home" class="header_link">Home</a>
    <a href="#bio" class="header_link">About me</a>
    <a href="#portfolio" class="header_link">Portfolio</a>
    <a href="#contact" class="header_link">Contact</a>

    </div> 

  </div>
</template>

<script>
export default {
  name: 'HeaderPage',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.header {
  display: flex;
  
}
.logo_left {
  width: 400px;
}
.link_right {
  width: 66%;
  display: flex;
  justify-content: space-between;
}
.header_link {
  font-style: normal;
  font-weight: 300;
  font-size: 18px;
  line-height: 21px;
  
  color: #E4E4E4;
/* text */
}
</style>
