<template>
  <div id="app">
    <div class="kakao">
      <top></top>
      <list></list>
    </div>
  </div>
</template>

<script>
import Top from './components/Top'
import List from './components/List'

export default {
  name: 'app',
  components: {
    top: Top,
    list: List
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
/*썸네일 방제목 리스트 구성*/
* {
    margin: 0;
    padding: 0;
  }
  ul {
    list-style: none;
  }
  .kakao {
    width: 20%;
    margin: 0 auto;
  }
</style>
