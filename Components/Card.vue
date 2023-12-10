<template>
    <div
        class="block max-w-sm p-16 card rounded-lg shadow-lg dark:bg-gray-800 dark:border-gray-700 dark:hover:bg-gray-700 flex-col">
        <h5 class="mb-2 text-2xl font-bold tracking-tight text-white text-center dark:text-white">{{ props.title }}</h5>
        <div class="my-4 flex justify-center" v-html="props.icon">
        </div>
        <p class="text-center font-normal text-white dark:text-gray-400">{{ props.description }}</p>
    </div>
</template>
<style>
.card {
    border-radius: 10px;
    background: rgba(166, 119, 255, 0.21);
}
</style>
<script setup>
const props = defineProps({
    title: String,
    icon: String,
    description: String
})
</script>