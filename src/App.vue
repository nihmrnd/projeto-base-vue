<script setup>
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <header>    
    <div class="wrapper">
      <HelloWorld msg="Hello world!" />
    </div>
  </header>

  <RouterView />
</template>

<style scoped>

</style>
