<template>
  <div id="app">
    <BaseCard number="4" stick="♥"></BaseCard>
    <BaseCard number="6" stick="♥"></BaseCard>
  </div>
</template>

<script>
import BaseCard from './components/BaseCard.vue'

export default {
  name: 'app',
  components: {
    BaseCard
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
  display: flex;
  flex-direction: row;
  justify-content: center;
  font-size: 60px;
}
</style>
