<template>
    <div class="faceContainer">
        <!-- eclipse (the purple circle) -->
        <div class="eclipse">
            <img src="../../public/image/eclipsebkg.png" alt="">
        </div>
        <!-- face image -->
        <div class="face">
            <img class="faceImg" src="../../public/image/face.png" alt="Image not loaded">
        </div>
        <!-- social Media seciton -->
        <div class="socialMedia">
            <!-- instargram logo -->
            <a target="_blank" class="igLogo  icon" href="https://www.instagram.com/mahdi_sadeghi18/"><img src="../../public/image/ig-logo.png" alt="instagram Logo"></a>
            <!-- twitter logo -->
            <a target="_blank" class="twitterLogo icon" href="https://twitter.com/Mehdi_Fyber"><img src="../../public/image/twitter-logo.png" alt="Twitter logo"></a>
            <!-- Github Logo -->
            <a target="_blank" class="githubLogo icon" href="https://github.com/MahdiSadeghi26"><img src="../../public/image/github-logo.png" alt=""></a>
        </div>
    </div>
</template>
<script>
export default {

}
</script>
<style lang="scss">
.faceContainer {
    bottom: 10px;

    // purple seciton (background)
    .eclipse {
        position: absolute;
        right: 0;
        width: 400px;
        opacity: .7;
        bottom: 0;
        img {
            width: 100%;
        }
    }
    // face seciton
    .face {
        position: absolute;
        right: 0;
        bottom: 0;

        img {
            width: 380px;
            height: 550px;
        }
    }
    .socialMedia{
        position: absolute;
        right: 10px;
        top:12rem;
        
        a{
            display: block;
            margin-bottom: 15px;
            img{
                width: 40px;
            }
        }
    }

}
</style>