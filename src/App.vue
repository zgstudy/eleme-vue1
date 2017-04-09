<template>
  <div id="app">
    <p>Hello Vue.js!</p>
    <p>Hello I am here!</p>
  </div>
</template>

<script>
let appData = require('../data/data.json')

console.log('appData::', appData)
export default {
  name: 'app',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<style lang="scss">
p {
  font-size: 20px;
  color: #f00;
  margin: 0;
  padding: 15px;
}
</style>
