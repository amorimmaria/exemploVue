<template>
  <div id="app">
    <Conteudo />
    <segundoConteudo/>
    <TerceiroConteudo/>
  </div>

</template>

<script>
import Conteudo from './components/Conteudo.vue'
import SegundoConteudo from './components/SegundoConteudo.vue'
import TerceiroConteudo from './components/TerceiroConteudo.vue'

export default {
  name: 'app',
  components: {
    Conteudo,
    SegundoConteudo,
    TerceiroConteudo
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: rgb(80, 55, 44);
  margin-top: 60px;
}
</style>
