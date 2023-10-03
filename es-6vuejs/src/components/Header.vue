<script setup>

</script>

<template>
  <div class="header">
    <div class="logo"><img src="https://grace.energy/wp-content/uploads/2022/03/grace-logo.svg" alt=""></div>
    <div class="nav">
        <div class="lang"><a href="#">ENGLISH</a></div>
        <div class="buy"><a href="#">BUY</a></div>
        <div class="user"><a href="#"><i class="bi bi-person"></i></a></div>
        <div class="bag"><a href="#"><i class="bi bi-bag"></i></a></div>
        <div class="menu"><a href="#">MENU</a></div>
        <div class="menu"><a href="#"><i class="bi bi-list"></i></a></div>
    </div>
  </div>
</template>

<style scoped lang="scss">
@use "../assets/styles/general.scss";
.header{
    height: 105px;
    background-color: #999B81;
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-wrap: wrap;
}
.header a{
  font-size: 17px;
}
.logo{
    margin: 0px 50px;
}
.nav{
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 25px;
    margin: 0px 50px;
}
.lang a:hover{
  color: #FBED3F;
}
.buy a{
  color: black;
  background-color: #FBED3F;
  padding: 5px 10px 0px 10px;
}

.user i{
  font-size: 25px;
  display: flex;
  align-items: center;
}

.bag i{
  font-size: 20px;
  display: flex;
  align-items: center;
}
.menu i{
  font-size: 25px;
  display: flex;
  align-items: center;
}
</style>
