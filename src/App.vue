<template>
  <div id="app">
    <HeaderComponent :header='header.toLocaleUpperCase()' />
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import HeaderComponent from './components/HeaderComponent.vue'

export default Vue.extend({
  name: 'app',
  components: {
    HeaderComponent
  },
  data () {
    return {
      header: 'ToDo List'
    }
  }
})
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

input {
  text-align: center;
}
</style>
