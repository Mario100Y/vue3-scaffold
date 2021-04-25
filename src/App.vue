<template>
  <div>
    <img alt="Vue logo" src="./assets/logo.png" />
    <div>
      <router-link to="/">Go to Home</router-link>
      <router-link to="/axios">Go to axios</router-link>
      <router-link to="/vuex">Go to vuex</router-link>
    </div>
    <router-view></router-view>
    <HelloWorld msg="Hello Vue 3 + TypeScript + Vite" />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import HelloWorld from './components/HelloWorld.vue'

export default defineComponent({
  name: 'App',
  components: {
    HelloWorld
  }
})
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
