<template>
<div class="hello">
  <h1>{{ msg }}</h1>
</div>
</template>

<script>
export default {
  name: 'hello',
  data() {
    return {
      msg: '蓄势待发...'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1 {
  font-weight: normal;
  color: #42b983;
}
</style>
