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
    grid-column: 2;
    grid-row: 1 /3;
    justify-self: end;
    align-content: end;
    height: 100%;
    .eclipse{
        width: 400px;
        grid-column: 2;
        opacity: .6;
        img{
            width: 100%;
        }
    }
}
</style>