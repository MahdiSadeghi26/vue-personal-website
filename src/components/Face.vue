<template>
    <div class="faceContainer">
        <div class="eclipse">
            <img src="../../public/image/eclipsebkg.png" alt="">
        </div>
    </div>
</template>
<script>
export default {

}
</script>
<style lang="scss">
.faceContainer {
    position: absolute;
    right: 0;
    bottom: 10px;
    .eclipse{
        width: 400px;
        grid-column: 2;
        opacity: .8;
        img{
            width: 100%;
        }
    }
}
</style>