<template>
  <p>测试前端自动化部署工具项目，现在已经更新，提交了代码到github</p>
  <span>现在在自动化部署项目，点击部署按钮，后看此项目是否更新为上面的文字</span>
  <span>呵呵哈哈哈，我又更新了</span>
  <HelloWorld msg="Welcome to Your Vue.js App"/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
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
