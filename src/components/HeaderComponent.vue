<template>
    <div>
        <img alt="Vue logo" src="../assets/logo.png">
        <h1>{{ header }}</h1>
        <input type="text" v-model="header">
    </div>
</template>

<script>
import Vue from 'vue'

export default {
  name: 'header',
  props: {
    header: {
      type: String,
      required: true
    }
  }
}
</script>
