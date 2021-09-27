<template>
  <Que que="問題" message="ゴルフにおいてPar5で2打でカップインするとスコアは次のどれになるでしょう?"/>
    <Ans ans="A:ボギー"/>
    <Ans ans="B:パー"/>
    <Ans ans="C:バーディー"/>
    <Ans ans="D:イーグル"/>
</template>

<script>
import Que from './components/Que.vue'
import Ans from './components/Ans.vue'


export default {
  name: 'App',
  components: {
    Que,
    Ans,
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
