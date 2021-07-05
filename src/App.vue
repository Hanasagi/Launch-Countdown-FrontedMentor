<template>
  <Countdown/>
</template>

<script>
import Countdown from './components/Countdown.vue'

export default {
  name: 'App',
  components: {
    Countdown
  }
}
</script>

<style>
#app {
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
