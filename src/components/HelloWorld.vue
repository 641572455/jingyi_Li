<template>
  <div class="hello">
     {{ mssg }}
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    mssg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
