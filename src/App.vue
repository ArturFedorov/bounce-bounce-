<template>
  <div class="app">
    <router-view></router-view>
  </div>
</template>

<script lang="ts">
  import { defineComponent } from 'vue'

  export default defineComponent({
    name: 'App'
  })
</script>

<style lang="scss">
  .app {
    width: 100%;
  }
</style>
