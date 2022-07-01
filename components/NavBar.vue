<template>
    <div class="border rounded-md bg-blue-300 flex justify-around p-4 font-bold">
        <p>Logotipo</p>
        <p class="ml auto">
            <nuxt-link to="/">Home</nuxt-link>
            <nuxt-link to="/AboutPage">About</nuxt-link>
            <nuxt-link to="/LoginPage">Login</nuxt-link>
        </p>
    </div>
</template>

<script lang="ts">
export default {
    name: "NavBarComponent"
}
</script>

<style>
</style>