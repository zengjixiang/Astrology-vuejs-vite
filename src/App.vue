<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <HelloWorld msg="歡迎來到 Universal Astrology 占星網" />
</template>

<!-- import -->
<script setup>
import HelloWorld from './components/Menu.vue'

</script>

<!-- Roboto Mono 字型  -->
@import url('https://fonts.googleapis.com/css?family=Roboto+Mono');

<!-- CSS -->
<style>
#app {
  font-family: 'Roboto Mono', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: ##cc3e50;
  margin-top: 60px;
}

#content {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #cc3e50;
  margin-top: 60px;
}

</style>