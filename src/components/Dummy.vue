<template>
  <div class="Dummy">
    <h1>{{ headerName }}</h1>
    <h3> Adding Two Numbers From Props</h3>
    <p>{{ x + y }} </p>
    <p>
      {{ mainParagraph }}
    </p>
  </div>
</template>

<script>
export default {
  name: 'Dummy',
  props: {
    headerName: {
      type: String,
      default: 'ahmed'
    },
    mainParagraph: String,
    x: Number,
    y: Number,
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
