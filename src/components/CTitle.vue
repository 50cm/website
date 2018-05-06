<template>
  <h1><span>{{count}}cm</span> 革命計画</h1>
</template>

<script>
export default {
  data () {
    return {
      count: 0
    }
  },
  mounted () {
    this.increment()
  },
  methods: {
    increment () {
      this.count++
      if (this.count < 50) {
        setTimeout(this.increment, 20)
      }
    }
  }
}
</script>

<style scoped>
h1 {
  margin: 0;
  color: white;
  font-size: 5vw;
}
span {
  font-family: 'C50cm-Number';
}
</style>
