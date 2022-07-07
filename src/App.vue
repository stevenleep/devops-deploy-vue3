<script setup lang="ts">
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <h1>测试Vue3的部署</h1>
  <span>应该会触发自动部署</span>
  <HelloWorld msg="Hello Vue3" />
  
  这个流水线经常出问题
</template>

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
