<script setup>

</script>

<template>
  <div class="pag3">
    <div class="container">
        <div class="title-pag3"><h2>THE ANSWER <br> IS GRACE</h2></div>
        <div class="card1">
            <div class="card1-left">
                  <div class="card1-left-top">
                     <div class="title-card1-left">1</div>
                     <div class="title-card1-right">AMINO ACIDS</div>
                  </div>
                  <div class="content-card1">
                     <h4>100% HIGHER</h4>
                     <h3>On average, GRACE yolks' amino acids level is 100% higher than other yolks</h3>
                     <div class="buy-card"><a href="">BUY</a></div>
                  </div>
            </div>
            <div class="card1-right">
               <img src="https://grace.energy/wp-content/uploads/2023/06/grace-box.jpg" alt="">
            </div>
        </div>
        <div class="card2">
         <div class="card2-right">
               <img src="https://grace.energy/wp-content/uploads/2023/05/grace-box-opened.jpg" alt="">
            </div>
         <div class="card2-left">
                  <div class="card2-left-top">
                     <div class="title-card2-left">2</div>
                     <div class="title-card2-right">ANTIOXIDANT</div>
                  </div>
                  <div class="content-card2">
                     <h4>AWARDED BY THE EUROPEAN ANTIOXIDANT INSTITUTE</h4>
                     <h3>The PAOT Score expresses the antioxidant power of a product, measuring its ability to neutralize free radicals. In April 2019, the European Antioxidant Institute (IEA) awarded GRACE a PAOT score of 65.4/g, demonstrating its very high antioxidant power.</h3>
                     <div class="buy-card"><a href="">BUY</a></div>
                  </div>
            </div>
            
        </div>
        <div class="card3">
         <div class="card3-left">
                  <div class="card3-left-top">
                     <div class="title-card3-left">3</div>
                     <div class="title-card3-right">PROTEIN</div>
                  </div>
                  <div class="content-card3">
                     <h4>73% MORE</h4>
                     <h3>A GRACE yolk boasts 33.7g per 100g. When combined with our egg whites – the only egg-based product to do so – the protein concentration increases to 48g per 100g.</h3>
                     <div class="buy-card"><a href="">BUY</a></div>
                  </div>
            </div>
            <div class="card3-right">
               <img src="https://grace.energy/wp-content/uploads/2023/05/grace-bag-1536x1295.jpg" alt="">
            </div>
        </div>
    </div>
  </div>
</template>

<style scoped lang="scss">
@use "../assets/styles/general.scss";
 .pag3{
    height: 2550px;
    background-color: #1a1a17;
 }
 .container{
   padding-top: 120px;
    margin: auto;
    max-width: 90vw;
 }
 .title-pag3{
    width: 500px;
    height: 160px;
 }
 .title-pag3 h2{
    font-size: 70px;
    color: #ffffff;
 }
 .card1{
    display: flex;
    height: 550px;
 }
 .card1-left{
    height: 100%;
    width: 60%;
    display: flex;
    flex-direction: column;
    justify-content: center;
    row-gap: 20px;
 }
 .card1-right{
   height: 100%;
   width: 40%;
   display: flex;
   justify-content: center;
   align-items: center;
 }
 .card1-right img{
   width: 100%;
   
 }
 
 .card1-left-top{
    display: flex;
    justify-content: center;
    align-content: center;
    height: 50px;
    width: 250px;
    gap: 10px;
 }
 .title-card1-left{
   display: flex;
   justify-content: center;
   align-items: center;
   width: 20%;
   height: 100%;
   
 }
 .title-card1-right{
   display: flex;
   justify-content: center;
   align-items: center;
   width: 80%;
   height: 100%;
 }
 .title-card1-right{
   font-size: 29px;
   color: white;
 }
 .title-card1-left{
   font-size: 25px;
   color: #FBED3F;
   border: 2px solid #FBED3F;
   border-radius: 50%;
 }
 .content-card1{
   margin-left: 60px;
   display: flex;
   flex-direction: column;
   row-gap: 20px;
 }
 .card1 h4{
   font-size: 18px;
   opacity: .6;
   color: #ffffff;
 }
 .card1 h3{
   font-size: 22px;
   color: #ffffff;
 }
 .buy-card a{
   color: black;
   background-color: #FBED3F;
   padding: 3px 8px 0px 8px;
 }

 .card2{
    display: flex;
    height: 550px;
    
 }
 .card2-left{
    height: 100%;
    width: 50%;
    display: flex;
    flex-direction: column;
    justify-content: center;
    row-gap: 20px;
 }
 .card2-right{
   height: 100%;
   width: 60%;
   
 }
 .card2-right img{
   width: 80%;
   
 }
 .card2-left-top{
    display: flex;
    justify-content: center;
    align-content: center;
    height: 50px;
    width: 250px;
 }
 .title-card2-left{
   display: flex;
   justify-content: center;
   align-items: center;
   width: 20%;
   height: 100%;
   
 }
 .title-card2-right{
   display: flex;
   justify-content: center;
   align-items: center;
   width: 80%;
   height: 100%;
   padding-left: 10px;
 }
 .title-card2-right{
   font-size: 29px;
   color: white;
 }
 .title-card2-left{
   font-size: 25px;
   color: #FBED3F;
   border: 2px solid #FBED3F;
   border-radius: 50%;
 }
 .content-card2{
   margin-left: 60px;
   display: flex;
   flex-direction: column;
   row-gap: 20px;
 }
 .card2 h4{
   font-size: 18px;
   opacity: .6;
   color: #ffffff;
 }
 .card2 h3{
   font-size: 22px;
   color: #ffffff;
 }
 .card3{
    display: flex;
    height: 550px;
    margin-top: 100px;
 }
 .card3-left{
    height: 100%;
    width: 60%;
    display: flex;
    flex-direction: column;
    justify-content: center;
    row-gap: 20px;
 }
 .card3-right{
   height: 100%;
   width: 40%;
   display: flex;
   justify-content: center;
   align-items: center;
 }
 .card3-right img{
   width: 100%;
 }
 .card3-left-top{
    display: flex;
    justify-content: center;
    align-content: center;
    height: 50px;
    width: 250px;
 }
 .title-card3-left{
   display: flex;
   justify-content: center;
   align-items: center;
   width: 20%;
   height: 100%;
   
 }
 .title-card3-right{
   display: flex;
   justify-content: center;
   align-items: center;
   width: 80%;
   height: 100%;
 }
 .title-card3-right{
   font-size: 29px;
   color: white;
 }
 .title-card3-left{
   font-size: 25px;
   color: #FBED3F;
   border: 2px solid #FBED3F;
   border-radius: 50%;
 }
 .content-card3{
   margin-left: 90px;
   display: flex;
   flex-direction: column;
   row-gap: 20px;
 }
 .card3 h4{
   font-size: 18px;
   opacity: .6;
   color: #ffffff;
 }
 .card3 h3{
   font-size: 22px;
   color: #ffffff;
   width: 70%;
 }
 @media (max-width: 1470px) {
  .card1-left, .card3-left{
    width: 50%;
  }
  .card2-right{width: 60%;}
}
</style>
