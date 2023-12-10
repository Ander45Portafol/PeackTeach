<template>
    <div class="w-screen h-screen body">
        <Navbar/>
    </div>
</template>
<style scoped>
.body {
    background: linear-gradient( #030316, #231145);
}
</style>
<script setup>
import { initFlowbite } from 'flowbite'
import Navbar from './Components/Navbar.vue';
onMounted(() => {
    initFlowbite();
})
</script>