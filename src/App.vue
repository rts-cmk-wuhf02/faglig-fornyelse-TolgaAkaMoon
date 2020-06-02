<template>
    <Calculator />
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
body {
  padding: 0;
  margin: 0;
  background: linear-gradient(to right, #00AAFF, #00FF6C);
}

#app {
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  padding: 0;
  margin: 0;
}
</style>
