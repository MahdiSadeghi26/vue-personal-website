<template>
 <h1 class="header-title">Mehdi Sadeghi</h1>
</template>

<script>


export default {
 
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
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  display: flex;
  flex-direction: column;
  .header-title{
    font-size: 30px;
    font-family: Montserrat-Bold;
    color: #8493BF;
    margin: 20px 0 0 41px;
    align-self: flex-start;

  }
}
</style>
