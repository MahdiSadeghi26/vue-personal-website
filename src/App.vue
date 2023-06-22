<template>
 <!-- title on the top of page! -->
 <h1 class="header-title">Mehdi Sadeghi</h1>
<!-- large Mehdi Sadeghi center of the page -->
<div class="fullName">
  <p class="lName">Mehdi</p>
  <p class="lName">Sadeghi</p>
</div>
<!--Skills component end of the page! -->
<Skills/>
<!-- Face component  -->
<!-- <Face/> -->
</template>

<script>
import Skills from './components/Skills.vue';
import Face from './components/Face.vue';
export default {
  components: { Skills, Face },
}
</script>

<style lang="scss">
*{
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}
@font-face {
  font-family: Montserrat-Bold;
  src: url("../public/fonts/Montserrat-Bold.ttf");
}
@font-face {
  font-family: Montserrat-Light;
  src: url("../public/fonts/Montserrat-Light.ttf");
}
@font-face {
  font-family: Montserrat-Medium;
  src: url("../public/fonts/Montserrat-Medium.ttf");
}
@font-face {
  font-family: Montserrat-Regular;
  src: url("../public/fonts/Montserrat-Regular.ttf");
}
@font-face {
  font-family: Montserrat-SemiBold;
  src: url("../public/fonts/Montserrat-SemiBold.ttf");
}
@font-face {
  font-family: Montserrat-Thin;
  src: url("../public/fonts/Montserrat-Thin.ttf");
}
body{
  background: url("../public/image/background.jpg")no-repeat fixed center;
  background-size: cover;
}
#app {
  height: 100vh;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  display: grid;
  grid-template-rows: repeat(3,1fr);
  grid-template-columns: repeat(2,1fr);
  
  .header-title{
    font-size: 30px;
    font-family: Montserrat-Bold;
    color: #8493BF;
    margin: 20px 0 0 41px;
    justify-self: start;
  }
  .fullName{
    font-family: Montserrat-Bold;
    color: #CEB3F2;
    font-size: 80px;
    text-align: left;
    grid-row: 2;
    justify-self: start;
    margin-left: 41px;
  }
}
</style>
