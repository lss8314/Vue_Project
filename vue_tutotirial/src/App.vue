<template>
  <div id="app">
    <Header />
   <List />
    <Footer />
  </div>
</template>

<script>
import Header from './components/common/Header.vue'
import List from './components/board/List.vue'
import Footer from './components/common/Footer.vue'


export default {
  name: 'app',
  components: {
    Header,
    List,
    Footer
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
