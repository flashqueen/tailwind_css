<template>
  <img alt="Vue logo" src="./assets/logo.png">

  <div class="container mx-auto bg-gray-200 rounded-xl shadow border p-8 m-10">
    <p class="text-3xl text-gray-700 font-bold mb-5">
      Hello World!
    </p>
    <p class="text-gray-500 text-lg">
      Vue and Tailwind CSS in action
    </p>
    <p class="text-rose-400 text-lg text-right">
      By Cinna
    </p>
  </div>
  <div class="p-4 m-4 space-x-4 border-l-2 border-blue-400 rounded-xl">
    <span>Teste de espaçamento no tailwind realizando padding e margin além de space-between</span>
    <span>
      Teste dois
    </span>
    <button class="bg-rose-400 px-4 py-1 rounded text-white focus:ring-2 ring-purple-400">Save</button>
  </div>
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
/* #app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
} */
</style>
