<template>
  <div id="app">
    <div id="app">
      <Form/>
      <Display/>
  </div>
  </div>
</template>

<script>
import Form from './components/Form.vue'
import Display from './components/Display.vue'
export default {
  name: 'app',
  components: {
    Form,
    Display
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
}
</style>
