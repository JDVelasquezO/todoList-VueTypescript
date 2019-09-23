<template>
    <div>
        <img alt="Vue logo" src="../assets/logo.png">
        <h1>{{ headerProp }}</h1>
    </div>
</template>

<script>
import Vue from 'vue'

export default Vue.extend({
  name: 'HeaderComponent',
  props: {
    headerProp: {
      type: String,
      required: true
    }
  }
})
</script>
