<template>
    <div class="skillsContainer">
        <p class="jobTitle">Junior Front-End Developer</p>
        <p class="skillsList">HTML  |  CSS  |  JS  |  Vue</p>
        <button><a href = "mailto: mahdisadeghi1381m@gmail.com">Hire Me !</a></button>
    </div>
</template>
<script>
export default {
    
}
</script>
<style lang="scss">
    .skillsContainer{
        justify-self: start;
        margin-left: 40px;
        align-self: center;
        grid-row: 3;
        color:#ffff ;
        .jobTitle{
            font-family: Montserrat-Regular;
            font-size: 32px;
        }
        .skillsList{
            font-family: Montserrat-Thin;
            font-size: 26px;
            margin-top: 20px;
        }
        button{
            margin-top: 20px;
            background: none;
            border: none;
            background-color: #8A7ED9;
            padding: 10px 40px;
            border-radius: 30px;
            font-size: 20px;
        }
        a{
            color: #ffff;
            font-family: Montserrat-SemiBold;
            text-decoration: none;
        }
    }
</style>