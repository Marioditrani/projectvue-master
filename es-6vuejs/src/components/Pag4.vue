<script setup>

</script>

<template>
  <div class="pag4">
    <div class="pag4-left">
        <h2>5 YEARS</h2>
        <P>OF RESEARCH & DEVELOPMENT</p>
    </div>
    <div class="pag4-right">
        <p class="p1">CERTIFIED LAB RESULTS</p>
        <p class="p2">100% NATURAL AND ORGANIC</p>
        <p class="p3">73% MORE PROTEIN</p>
        <p class="p4">KETO DIET FRINDLY</p>
        <p class="p5">HIGHEST ANTIOXIODANT RATE</p>
        <p class="p6">100% HIGHER LEVEL OF AMINO ACID</p>
    </div>
  </div>
</template>

<style scoped lang="scss">
@use "../assets/styles/general.scss";
.pag4{
    height: 600px;
    display: flex;
}
.pag4-left, .pag4-right{
    width: 50%;
    height: 100%;
}
.pag4-left{
    background-color: #FBED3F;
    color: #999b81;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
}
.pag4-left h2 {
    font-size: 100px;
}
.pag4-left p {
    font-size: 50px;
    width: 50%;
    margin-left: 60px;
}
.pag4-right{
    background-color: #999b81;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
}
.pag4-right p{
    font-size: 30px;
    width: 100%;
    padding-left: 250px;
    color: #FFFFFF;
    margin-bottom: 10px;
}
.p1{
    opacity: 1;
}
.p2{
    opacity: 0.95;
}
.p3{
    opacity: .7;
}
.p4{
    opacity: .6;
}
.p5{
    opacity: .5;
}
.p6{
    opacity: .4;
}
</style>
