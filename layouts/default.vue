<template>
    <div>
        <NavBar/>
        <Nuxt />
    </div>
</template>

<script land="ts">
import NavBar from '@/components/NavBar.vue'
export default {
    name: "default",
    components: {
        NavBar
    }
}
</script>

<style>
</style>