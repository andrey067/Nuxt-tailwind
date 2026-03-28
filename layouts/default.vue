<template>
  <div>
    <NavBar />
    <Nuxt />
  </div>
</template>

<script lang="ts">
import NavBar from '@/components/NavBar.vue'
export default {
  name: 'Default',
  components: {
    NavBar,
  },
}
</script>

<style></style>
