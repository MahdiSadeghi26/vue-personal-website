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
      <Skills />

    </div>
    <!-- Right side Container -->
    <div class="rightSide">
      <!-- purple ecplipse -->
      <img class="eclipse" src="/public/image/eclipse.png" alt="image 404">
      <!-- face -->
      <img src="/public/image/face.png" alt="Image 404" class="face">
      <!-- social media section -->
      <div class="socialMedia">
        <!-- instagram -->
        <a target="_blank" href="https://www.instagram.com/mahdi_sadeghi18/" class="instagram" title="My Instagram">
          <img class="instagramLogo" src="/public/image/ig-logo.png" alt="Image 404"></a>
        <!-- twitter -->
        <a target="_blank" href="https://twitter.com/Mehdi_Fyber" title="My Twitter" class="twitter">
          <img class="twitterLogo" src="/public/image/twitter-logo.png" alt="Image 404"></a>
        <!-- gitgub -->
        <a target="_blank" href="https://github.com/MahdiSadeghi26" title="My Github" class="github">
          <img class="githubLogo" src="/public/image/github-logo.png" alt="Image 404"></a>

      </div>
    </div>
  </div>
</template>

<style scoped lang="scss">
.container {
  background: url("/image/background.jpg")no-repeat fixed center;
  background-size: cover;
  width: 100vw;
  height: 100vh;
  display: grid;
  grid-template-columns: 50% 50%;

  // left side section
  .leftSide {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    padding: 30px 0 15px 41px;

    h1 {
      color: #8493BF;
      font-weight: 700;
      font-size: 30px;

      &:hover {
        color: #9caee4;
      }
    }

    .fullName {
      color: #CEB3F2;
      font-weight: 700;
      font-size: 70px;
    }
  }

  // Right side section
  .rightSide {
    position: relative;

    .eclipse {
      position: absolute;
      bottom: 0;
      right: 0;
      width: 40%; 
      height: 75vh;
      opacity: .7;
    }

    .face {
      position: absolute;
      right: 10px;
      bottom: 0;
      width: 35%;
      height: 65%;
    }
    // social Media
    .socialMedia{
      position: absolute;
      right: 10px;
      top: 30%;
      a{
        display: block; 
        img{
          width: 35px;
          height: auto;
          margin: 10px 0;
        }
        .githubLogo{
          width: 40px;
        }
      }
    }
  }
}
// Media query
// max 1200px
@media screen and (max-width:1200px) {
  .container{
    .leftSide{
      h1{
      font-size: 28px; 
    }
    .fullName{
      font-size: 60px;
    }

    }
    .rightSide{
      .eclipse{
        width: 47%;
        height: auto;
      }
      .face{
        width: 40%;
      }
      .socialMedia{
        top: 20vh;
        a{
          img{
            width: 30px;
          }
          .githubLogo{
            width: 35px;
            
          }
        }
      }
    }
  }
}
// 992px
@media screen and (max-width:992px) {
  .container{
    .leftSide{
      h1{
        font-size: 26px;
      }
      .fullName{
        font-size: 50px;
      }
    }
    .rightSide{
      .eclipse{
        height: 80vh;
      }
      .socialMedia{
        top: 25%;
      }
    }
  }
}
</style>
