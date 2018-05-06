<template>
  <div id="app">
    <c-header />
    <section>
      学生が世界を変えるなんてムリだ。<br />
      限られた権利、少ない資金、足りない時間。<br />
      でも、世界には約４億人の高校生がいる。<br />
      みんなが協力すれば、世界はきっと変わる。<br />
      自分の周りから行動しよう。発信しよう。<br />
      学生こそが世界を変えるんだ。<br />
      さあ、半径 50cm の改革を始めよう。
    </section>
  </div>
</template>

<script>
import CHeader from './components/CHeader'

export default {
  name: 'App',
  components: {
    CHeader
  }
}
</script>

<style>
@font-face {
  font-family: 'Makinas';
  src: url('./assets/Makinas-Scrap-5.otf') format('opentype');
}
html, body {
  margin: 0;
  font-family: 'Makinas';
}
section {
  width: 100%;
  padding: 50px;
  padding-left: 10vw;
  box-sizing: border-box;
  overflow: hidden;
}
</style>
