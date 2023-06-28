<template >
    <div class="skillsContainer">
        <!-- job title -->
        <p class="jobTitle">Junior Front-End Developer</p>
        <!-- skills i have -->
        <p class="mySkills">HTML | CSS | JS | Vue</p>
        <!-- hire me button -->
        <button class="hireBtn"><a href="mailto:mahdisadeghi1381m@gmail.com">Hire Me !</a></button>
    </div>
</template>
<script>
export default {

}
</script>
<style lang="scss" scoped>
.skillsContainer {
    display: flex;
    flex-direction: column;
    justify-content: center;
    color: #ffff;
    margin-bottom: 40px;
    width: 420px;
    .jobTitle {
        font-weight: 400;
        font-size: 30px;
        margin-bottom: 20px;
    }
    .mySkills {
        font-weight: 100;
        font-size: 26px;
        text-align: center;
        margin-bottom: 20px;
    }
    .hireBtn {
        background-color: #8A7ED9;
        border: none;
        padding: 15px 50px;
        border-radius: 25px;
        font-size: 20px;
        align-self: center;
        font-weight: 600;
        &:hover {
            background-color: #a79de7;
        }
        a {
            text-decoration: none;
            color: #ffff;
        }
    }
}

// media query
// 1200px
@media screen and (max-width:1200px) {
    .skillsContainer {
        // align-items: center;
        width: 350px;
        .jobTitle,.mySkills {
            font-size: 24px;
        }
        .hireBtn {
            padding: 10px 30px;
            font-size: 18px;
        }
    }
}
// 992px
@media screen and (max-width:992px) {
    .skillsContainer{
        .jobTitle{
            font-size: 23px;
        }
        .mySkills{
            font-size: 22px;
            
        }
    }
}
</style>