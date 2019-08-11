<template>
  <div id="app">
    <div class="DANprefix-flex DANprefix-justify-center bg-gray-200 DANprefix-flex-col">
      <h1 class="DANprefix-text-5xl">Grid test</h1>
    </div>
    <div class="DANprefix-flex DANprefix-mb-4 DANprefix-justify-center">
      <div class="DANprefix-w-1/3 DANprefix-bg-gray-400">
        <img alt="Vue logo" class="DANprefix-m-auto" src="./assets/logo.png" />
      </div>
    </div>
    <div class="DANprefix-flex DANprefix-bg-gray-200">
      <div
        class="DANprefix-flex-1 DANprefix-text-gray-700 DANprefix-text-center DANprefix-bg-gray-400 DANprefix-px-4 DANprefix-py-2 DANprefix-m-2"
      >flex test</div>
      <div
        class="DANprefix-flex-1 DANprefix-text-gray-800 DANprefix-text-center DANprefix-bg-gray-500 DANprefix-py-2 DANprefix-m-2"
      >flex test</div>
      <div
        class="DANprefix-flex-1 DANprefix-text-gray-700 DANprefix-text-center DANprefix-bg-gray-400 DANprefix-py-2 DANprefix-m-2"
      >flex test</div>
    </div>
    <button class="DANprefix-text-white DANprefix-py-2 DANprefix-px-4  DANprefix-bg-dan-300 hover:DANprefix-bg-dan-600">test for theme DAN color</button>
     <button class="btn DANprefix-bg-dan-300 hover:DANprefix-bg-dan-600">test for @apply function</button>
     If you'd like to prefix your own utilities as well, just add the prefix to the class definition.
     <br>
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
