<template>
  <div id="app">
    <h3>Arithmetic Calculator with Vue</h3>
    <Calculator />
    <br />
    <span>
      <strong>Made with <span class="heart">♥</span> by <a href="http://fantasticfoluwa.me">MORONFOLUWA</a></strong>
    </span>
  </div>
</template>

<script>
import Calculator from './components/Calculator.vue'

export default {
  name: 'app',
  components: {
    Calculator
  }
}
</script>

<style>
a{
  text-decoration: none;
}
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
.heart {
  color: #f00;
  font-size: 30px;
}
</style>
