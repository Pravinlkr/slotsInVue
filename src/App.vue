<template>
  <c-card></c-card>
</template>

<script>
import cCard from './components/cCard.vue'

export default {
  name: 'App',
  components: {
    cCard,
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
