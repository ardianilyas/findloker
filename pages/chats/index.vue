<template>
    <ChatLayout>
        <div class="flex flex-col justify-between h-full">
            <div class="flex flex-col gap-10">
                <div class="bg-blue-200 max-w-lg text-xs sm:text-base inline-block px-6 py-3 rounded-full rounded-bl-none w-fit">
                    Hello, thank you for applying to our recruitment. We will contact you soon.
                </div>
                <div class="bg-gray-200 max-w-lg text-xs sm:text-base inline-block px-6 py-3 rounded-full rounded-br-none self-end w-fit">
                    Hello, thank you for responding my application. Glad to hear from you.
                </div>
            </div>
    
            <div class="flex items-center gap-4">
                <Input class="max-w-xl" placeholder="Type here..." />
                <button class="bg-blue-600 hover:bg-blue-700 px-5 py-3 rounded-sm text-white font-medium transition-all ease-in-out">
                    <Send class="w-4 h-4" />
                </button>
            </div>
        </div>
    </ChatLayout>
</template>

<script setup>
import ChatLayout from '~/components/ChatLayout.vue';
import { Send } from 'lucide-vue-next';

definePageMeta({
    layout: false
})
</script>