<template>
  <div id="app">
    <firstView />
    <advantages />
  </div>
</template>

<script>
import firstView from './components/firstView.vue'
import advantages from "@/components/advantages";

export default {
  name: 'App',
  components: {
    firstView,
    advantages
  }
}
</script>

<style lang="scss">

</style>
