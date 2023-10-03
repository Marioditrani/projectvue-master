<script setup>

</script>

<template>
  <div class="pag5">
    <div class="container">
        <div class="title-pag5"><h2>3 METABOLIC BOOSTERS</h2></div>
        <div class="container-bar">
            <div class="bar1">
                 <h3>AMINO ACIDS</h3>
                <a href=""><i class="bi bi-plus"></i></a>
            </div>
            <div class="bar2">
                 <h3>ANTIOXIDANTS</h3>
                 <a href=""><i class="bi bi-plus"></i></a>
            </div>
            <div class="bar3">
                 <h3>PROTEIN</h3>
                 <a href=""><i class="bi bi-plus"></i></a>
            </div>
        </div>
    </div>
  </div>
</template>

<style scoped lang="scss">
@use "../assets/styles/general.scss";
.pag5{
    height: 900px;
    background-color:#1a1a17 ;
    padding-top: 100px;
}
.container{
    height: 800px;
    max-width: 85%;
    margin: auto;
}
.title-pag5{
    height: 35%;
    display: flex;
    align-items: center;
}
.title-pag5 h2{
    font-size: 70px;
    width: 40%;
    color: #FFFFFF;
}
.container-bar{
    height: 520px;
    
}
.bar1, .bar2, .bar3{
    height: 20%;
    display: flex;
    align-items: center;
    justify-content: space-between;
    font-size: 30px;
    color: #FFFFFF;
    border-top: 1px solid white;
}
.bar1 i, .bar2 i, .bar3 i{
    font-size: 80px;
}
.bar2{
    opacity: .5;
}
.bar3{
    opacity: .3;
    border-bottom: 1px solid white;
}
</style>
