<script setup>

</script>

<template>
  <div class="pag2">
    <div class="title-pag2">
        A LONGER, HEALTHIER AND HAPPIER LIFE
    </div>
    <p class="text-pag2-first">Our lives are full of factors that accelerate aging: processed food, a lack of physical activity, and increased stress. What if there was a natural way to age better?</p>
    <p class="text-pag2"> 
        <span class="logo-text">GRACE</span>
        is 100% artisanal nutrition for exceptional performance and well-being.
        <br>
        The state-of-the-art in advanced nutrition from eggs and grape seeds.
        <br>
        <span>GRACE</span>
        optimizes your health to perform at the highest physical and mental level, empowering you to be the best version of yourself at work, at home, and in training.


    </p>
  </div>
</template>

<style scoped lang="scss">
@use "../assets/styles/general.scss";
.pag2{
    height: 950px;
    background-color: #f0eee9;
    color: #3c3c3c;
    
}
.title-pag2,.text-pag2,.text-pag2-first{
    margin: 0px 150px;
}
.title-pag2{
    padding-top: 250px;
    font-size: 70px;
    width: 50%;
}
.text-pag2-first{
    margin-top: 100px;
    font-size: 25px;
    width: 60%;
    margin-bottom: 30px;
}
.text-pag2{
    font-size: 25px;
    width: 70%;
    
}
@media (max-width: 1130px) {
    .title-pag2{
    font-size: 60px;
    padding-top: 210px;
    }
    .text-pag2-first{
        margin-top: 60px;
    }
}
@media (max-width: 950px) {
    .title-pag2{
    padding-top: 180px;
    }
}
@media (max-width: 820px) {
    .title-pag2{
    font-size: 50px;
    width: 90%;
    margin: auto;
    }
    .text-pag2, .text-pag2-first{
        font-size: 24px;
    }
    .title-pag2,.text-pag2,.text-pag2-first{
    margin: 0px 130px;
    }
    .text-pag2-first{
        margin-top: 50px;
    }
}
</style>
