<template>
    <header class="bg-white shadow-sm px-8 sm:px-10 md:px-12 py-6 w-full">
        <div class="max-w-xl flex gap-10 items-center">
            <NuxtLink to="/">
                <MoveLeft />
            </NuxtLink>
            <Input placeholder="Search chat" />
        </div>
    </header>
</template>

<script setup>
import { MoveLeft } from 'lucide-vue-next';
</script>