<template>
  
  <Services />
  <Utilities />
  <Seedboxes />
  
</template>

<script>
import Services from '@/components/Services.vue'
import Utilities from '@/components/Utilities.vue'
import Seedboxes from '@/components/Seedboxes.vue'

export default {
  components: {
    Services,
    Utilities,
    Seedboxes
  }
}
</script>

<style>
body {
  background-color: #1e1e1e;
}
</style>
