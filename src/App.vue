<script setup>
 
</script>

<template>
  <div class="container">
   <div class="leftSide"><h1>Mehdi Sadeghi</h1></div>
   <div class="rightSide"></div>
  </div>
</template>

<style scoped lang="scss">
.container{
    background: url("/image/background.jpg")no-repeat fixed center;
    background-size: cover;
    width: 100vw;
    height: 100vh;
    display: grid;
    grid-template-columns: 50% 50%;
    .leftSide{
      display: flex;
      flex-direction: column;
      padding: 30px 0 15px 41px;
      h1{
      color: #8493BF;
      font-family: "Montserrat";
      font-weight: 700;
      font-size: 30px;
      &:hover{
        color: #9caee4;
      }
    }
    }
    .rightSide{
      
    }
}
</style>
