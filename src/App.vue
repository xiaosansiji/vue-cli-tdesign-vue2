<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <t-button>按钮</t-button>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import { Button as TButton } from 'tdesign-vue/es';

export default {
  name: 'App',
  components: {
    HelloWorld,
    TButton,
  },
  data() {
    return {
      current: 1,
    };
  },
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
