<template>
  <h1>{{ msg }}</h1>

  <p>
    |
    <a href="//zengjixiang.github.io/astrology/" target="_blank">占星資訊</a> |

    <a href="../house.html" target="_blank">十二宮位</a> |
    
    <a href="https://vitejs.dev/guide/features.html" target="_blank">Vite Documentation</a> |
    <a href="https://v3.vuejs.org/" target="_blank">Vue 3 Documentation</a>
  </p>

  <button @click="state.count++">count is: {{ state.count }}</button>
  <p>
    此系統由  
    <code>Ji-Xiang </code>
    開發維護
  </p>
</template>

<script setup>
import { defineProps, reactive } from 'vue'

defineProps({
  msg: String
})

const state = reactive({ count: 0 })
</script>

<style scoped>
a {
  color: #42b983;
}
</style>