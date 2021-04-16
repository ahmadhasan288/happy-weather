<template>
  <div>
    <Dummy :header-name="name" :main-paragraph="'hesham is not a good man'" :x=10 :y=5 />
      <div>{{ count }}</div>
      <div>{{ name }}</div>
  </div>
</template>

<script>

import Dummy from './components/Dummy.vue'

export default {
  name: 'App',
  components: {
    Dummy
  },
  data: function () {
    return {
      count: 0,
      name: "Ahmad"
    }
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
