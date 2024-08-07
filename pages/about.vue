<template>
    <div>
        <NavBar />
        <div class="container mx-auto p-4">
            <h1 class="text-4xl font-bold mb-4">HFMS</h1>
            <p class="text-lg">Information about the Health Facilities Management System.</p>
        </div>
    </div>
</template>

<script>
import NavBar from '~/components/NavBar.vue';

export default {
    components: {
        NavBar,
    },
}
</script>

<style scoped>
/* Add any scoped styles for this page here */
</style>