<template>
  <div id="app">
    <c-header />
  </div>
</template>

<script>
import CHeader from './Components/CHeader'

export default {
  name: 'App',
  components: {
    CHeader
  }
}
</script>

<style>
html, body {
  width: 100%;
  height: 100%;
  margin: 0;
}
#app {
  height: 100%;
}
</style>
