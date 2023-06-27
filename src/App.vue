<script setup>
 import Skills from './components/Skills.vue';
</script>

<template>
  <!-- main container -->
  <div class="container">
    <!-- left side container -->
    
   <div class="leftSide">
    <!-- header name -->
    <h1>Mehdi Sadeghi</h1>
    <!-- middle page fullName -->
    <div class="fullName">
      <p class="fName">Mehdi</p>
      <p class="lName">Sadeghi</p>
    </div>
  <Skills/>
  
  </div>
   <!-- Right side Container -->
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
      justify-content: space-between;
      padding: 30px 0 15px 41px;
      h1{
      color: #8493BF;
      font-weight: 700;
      font-size: 30px;
      &:hover{
        color: #9caee4;
      }
      }
      .fullName{
        color: #CEB3F2;
        font-weight: 700;
        font-size: 70px;
      }    
    }
    .rightSide{
      
    }
}
</style>
