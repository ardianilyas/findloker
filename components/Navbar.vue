<template>
    <nav class="flex justify-between items-center px-8 sm:px-10 md:px-12 py-4">
        <NuxtLink to="/" class="text-xl font-medium">Findloker</NuxtLink>
        <div class="flex items-center gap-4">
            <NuxtLink to="/chats">
                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-message-circle-icon lucide-message-circle"><path d="M7.9 20A9 9 0 1 0 4 16.1L2 22Z"/></svg>
            </NuxtLink>
            <LoginButton />
            <!-- <NuxtLink to="/">
                <div class="w-10 h-10 bg-gray-300 rounded-full flex justify-center items-center">FL</div>
            </NuxtLink> -->
        </div>
    </nav>
</template>

<script setup lang="ts">
import LoginButton from './LoginButton.vue';
</script>