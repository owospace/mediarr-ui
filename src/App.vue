<template>
  
  <Header />
  <Applications />
  
</template>

<script>
import Header from '@/components/Header.vue'
import Applications from '@/components/Applications.vue'

export default {
  components: {
    Header,
    Applications
  }
}
</script>

<style>
body {
  background-color: #1e1e1e;
}
</style>
