<template>
  <div class="container">
    <dew-editor></dew-editor>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'App',
})
</script>

<style lang="scss">
.container {
  height: 98vh;
  border: 1px solid red;
}
</style>
