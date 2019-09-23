<template>
    <div>
        <input type="text"
            :value="value"
            @input="($event) => $emit('input', $event.target.value)"
        >
    </div>
</template>

<script lang='ts'>
import Vue from 'vue'

export default Vue.extend({
  name: 'FormComponent',
  props: {
    value: String
  }
})
</script>
