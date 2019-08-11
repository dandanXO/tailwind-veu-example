<template>
  <div id="app">
    <div class="flex justify-center bg-gray-200 flex-col">
      <h1 class="text-5xl">Grid test</h1>
    </div>
    <div class="flex mb-4 justify-center">
      <div class="w-1/3 bg-gray-400">
        <img alt="Vue logo" class="m-auto" src="./assets/logo.png" />
      </div>
    </div>
    <div class="flex bg-gray-200">
      <div
        class="flex-1 text-gray-700 text-center bg-gray-400 px-4 py-2 m-2"
      >flex test</div>
      <div
        class="flex-1 text-gray-800 text-center bg-gray-500 px-4 py-2 m-2"
      >flex test</div>
      <div
        class="flex-1 text-gray-700 text-center bg-gray-400 px-4 py-2 m-2"
      >flex test</div>
    </div>
    <button class=" text-white py-2 px-4  bg-dan-300 hover:bg-dan-600">test for theme DAN color</button>
     <button class="btn bg-dan-300 hover:bg-dan-600">test for @apply function</button>
    <HelloWorld msg="Welcome to Your Vue.js App" />
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";

export default {
  name: "app",
  components: {
    HelloWorld
  }
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
