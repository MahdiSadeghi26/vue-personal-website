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
    .eclipse{
        right: 0;
        position: absolute;
        width: 400px;
        opacity: .8;
        bottom: 0;
        z-index: -1;
        img{
            width: 100%;
        }
    }
    // face seciton
    .face{
        position: absolute;
        right: 0;
        bottom: 0;
        img{
            width: 380px;
            height: 550px;
        }
    }
    
}
</style>