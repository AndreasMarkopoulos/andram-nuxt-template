<template>
    <div class="m-3 p-3 border rounded">
        <h3 class="text-xl font-bold mb-3">
            Pinia store example:
        </h3>
        <div class="flex flex-col items-center gap-3">
            <div class="flex items-center gap-x-3">
                <div>Count:</div>
                <div class="border rounded p-3">
                    {{ counterStore.count }}
                </div>
            </div>
            <button
                class="bg-transparent hover:bg-blue-500 text-blue-700 font-semibold hover:text-white py-2 px-4 border border-blue-500 hover:border-transparent rounded cursor-pointer"
                @click="counterStore.increment"
            >
                Increment
            </button>
        </div>
    </div>
</template>

<script setup lang="ts">
import { useCounterStore } from '~/stores/counterStore';

const counterStore = useCounterStore();
</script>

<style scoped>

</style>
