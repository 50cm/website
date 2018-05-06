<template>
  <header>
    <h2>学生が、世界を変える。</h2>
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
  width: 100%;
  height: 100vh;
  background-image: url('../assets/back.jpg');
  background-size: cover;
  background-position: center;
  padding: 30vh 0 0 10vw;
  box-sizing: border-box;
}
h2 {
  color: white;
  margin: 0;
}
</style>
