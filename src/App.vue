<script setup>
import { RouterView } from 'vue-router'
import Header from './components/Header.vue'
import Footer from './components/Footer.vue'
</script>

<template>
  <body>
  <div class="container flex flex-col max-w-screen-xl min-h-screen mx-auto bg-cover">
    <Header />
    <main>
      <RouterView />
    </main>
    <Footer />
  </div>
  </body>
</template>

<style scoped>
.container {
}
</style>
