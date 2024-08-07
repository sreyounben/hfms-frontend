<template>
    <nav class="bg-blue-500 p-4">
        <ul class="flex space-x-4">
            <li><nuxt-link to="/" class="text-white">Home</nuxt-link></li>
            <li><nuxt-link to="/about" class="text-white">About HFMS</nuxt-link></li>
            <!-- Add more navigation links as needed -->
        </ul>
    </nav>
</template>

<script>
export default {
    name: 'NavBar',
}
</script>

<style scoped>
/* Add any scoped styles for this component here */
</style>