<script setup>

</script>

<template>
  <div class="pag1">
    <div class="font-home"><h1>GRACE</h1></div>
    <img src="https://grace.energy/wp-content/uploads/2022/03/waves-image-min-2048x866.png" alt="" class="wave" >
  </div>
</template>

<style scoped lang="scss">
@use "../assets/styles/general.scss";
.pag1{
  background-color: #999B81;
  height: 1000px;
  display: flex;
  justify-content: center;
}

.font-home h1{
font-size: 13.5vw;
font-weight: 350;
line-height: 3.3em;
color: white;
display:inline-block;
-webkit-transform:scale(2,1);
}
.wave{
  position: absolute;
  top: 570px;
  height: 600px;
  width: 100%;
}
</style>
