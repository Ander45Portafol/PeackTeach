<template>
    <div class="w-screen h-screen body">
        <Navbar />
        <main class=" container pt-40 mx-auto h-full">
            <div class="home">

            </div>
            <div class="features flex-col w-full">
                <div class="w-full flex">
                    <div class="h-9 w-1 bg-white"></div>
                    <h1 class="text-white font-bold text-3xl ml-4">Features</h1>
                </div>
                <div class="w-full flex justify-between mt-8">
                    <Card title="Software quality" icon='<svg xmlns="http://www.w3.org/2000/svg" width="48" height="48" viewBox="0 0 24 24"
                style="fill: rgba(255, 255, 255);transform: ;msFilter:;">
                <path
                    d="m7.375 16.781 1.25-1.562L4.601 12l4.024-3.219-1.25-1.562-5 4a1 1 0 0 0 0 1.562l5 4zm9.25-9.562-1.25 1.562L19.399 12l-4.024 3.219 1.25 1.562 5-4a1 1 0 0 0 0-1.562l-5-4zm-1.649-4.003-4 18-1.953-.434 4-18z">
                </path>
            </svg>' description="Quality software and optimizations process" />
                    <Card title="Multiplatform"
                        icon='<svg xmlns="http://www.w3.org/2000/svg" width="48" height="48" viewBox="0 0 24 24" style="fill: rgba(255, 255, 255);transform: ;msFilter:;"><path d="M20 3H7c-1.103 0-2 .897-2 2v2H4c-1.103 0-2 .897-2 2v10c0 1.103.897 2 2 2h6c1.103 0 2-.897 2-2h8c1.103 0 2-.897 2-2V5c0-1.103-.897-2-2-2zM9.997 19H4V9h6l-.003 10zm10-2H12V9c0-1.103-.897-2-2-2H7V5h13l-.003 12z"></path></svg>'
                        description="Solutions multiplatform, guarantee high accessibility and flexibility" />
                    <Card title="Security"
                        icon='<svg xmlns="http://www.w3.org/2000/svg" width="48" height="48" viewBox="0 0 24 24" style="fill: rgba(255, 255, 255);transform: ;msFilter:;"><path d="M12 2C9.243 2 7 4.243 7 7v2H6c-1.103 0-2 .897-2 2v9c0 1.103.897 2 2 2h12c1.103 0 2-.897 2-2v-9c0-1.103-.897-2-2-2h-1V7c0-2.757-2.243-5-5-5zM9 7c0-1.654 1.346-3 3-3s3 1.346 3 3v2H9V7zm9.002 13H13v-2.278c.595-.347 1-.985 1-1.722 0-1.103-.897-2-2-2s-2 .897-2 2c0 .736.405 1.375 1 1.722V20H6v-9h12l.002 9z"></path></svg>'
                        description="Use protocols and develop practices to security guarantee " />
                </div>
            </div>
            <div class="services"></div>
            <div class="products"></div>
        </main>
    </div>
</template>
<style scoped>
.body {
    background: linear-gradient(#030316, #231145);
}
</style>
<script setup>
import { initFlowbite } from 'flowbite'
import Navbar from './Components/Navbar.vue';
import Card from './Components/Card.vue';
onMounted(() => {
    initFlowbite();
})
</script>