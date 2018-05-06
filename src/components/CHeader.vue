<template>
  <header>
    <c-title />
  </header>
</template>

<script>
import CTitle from './CTitle'
export default {
  components: {
    CTitle
  }
}
</script>

<style scoped>
header {
  width: 100vw;
  height: 100vh;
  background-image: url('../assets/back.jpg');
  background-size: cover;
  background-position: center;
  padding: 30vh 30vw 0 0;
  box-sizing: border-box;
  text-align: right;
}
</style>
