<script setup lang="ts">
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <h1>测试Vue3的部署</h1>
  <span>应该会触发自动部署</span>
  
  20220708 01:41
  {{ new Date() }}
  
  <HelloWorld msg="Hello Vue3" />
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
