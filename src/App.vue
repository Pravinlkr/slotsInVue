<template>
  <!--Default card-->
  <c-card>
    <template v-slot:Header></template>
    <template v-slot:Title></template>
    <template v-slot:Body></template>
    <template v-slot:Footer></template>
  </c-card>

  <!--Passing values in card slots-->
  <c-card>
    <template v-slot:Header>
      <img src="./assets/manual.jpg" alt="default Image">
    </template>
    <template v-slot:Title>
      <h3>Manual Title</h3>
    </template>
    <template v-slot:Body></template>
    <template v-slot:Footer>
      <button>Click Me</button>
    </template>
  </c-card>
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
  margin-top: 60px;
}
</style>
