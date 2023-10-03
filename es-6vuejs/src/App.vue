<script>
import Header from './components/Header.vue'
import Home from './components/Home.vue'
import Pag2 from './components/Pag2.vue'
import Pag3 from './components/Pag3.vue'

export default{
  components:{
    Home,
    Header,
    Pag2,
    Pag3,
  }
}
</script>

<template>
  <div>
    <Header />
    <Home />
    <Pag2 />
    <Pag3 />
    
  </div>
</template>

<style scoped>

</style>
