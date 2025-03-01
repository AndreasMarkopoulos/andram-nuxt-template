<template>
    <div class="flex">
        <div class="m-3 p-3 border rounded">
            <h1 class="text-3xl font-bold">
                Welcome to the Andram nuxt-template!
            </h1>
            <h2 class="text-2xl font-bold">
                This is a starter template with the following configured:
            </h2>
            <ul class="list-disc list-inside mt-3">
                <li>Nuxt</li>
                <li>Typescript</li>
                <li>Tailwind</li>
                <li>Pinia</li>
            </ul>
        </div>
        <pinia-store-demo />
    </div>
</template>

<script setup lang="ts">
import PiniaStoreDemo from '~/components/PiniaStoreDemo.vue';
</script>

<style scoped>

</style>
