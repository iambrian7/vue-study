<template>
  <div id="first-component">
  <h1>{{ msg}}</h1>
  </div>
</template>

<script>
module.exports = {
  name: 'first-component',
  data () {
    return {
      msg: 'Welcome to Your first component'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.class {
   
    background-color: #cccccc;
    width: 100wh;
    height: 100vh;
}

</style>
