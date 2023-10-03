<script>
import Header from './components/Header.vue'
import Home from './components/Home.vue'
import Pag2 from './components/Pag2.vue'
import Pag3 from './components/Pag3.vue'
import Pag4 from './components/Pag4.vue'
import Pag5 from './components/Pag5.vue'

export default{
  components:{
    Home,
    Header,
    Pag2,
    Pag3,
    Pag4,
    Pag5
  }
}
</script>

<template>
  <div>
    <Header />
    <Home />
    <Pag2 />
    <Pag3 />
    <Pag4 />
    <Pag5 />
  </div>
</template>

<style scoped>

</style>
