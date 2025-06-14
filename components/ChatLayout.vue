<template>
    <div class="min-h-screen flex flex-col">
      <ChatHeader />

      <div class="flex flex-1 min-h-0">
        <div class="bg-gray-50 p-8 flex-3/12 flex flex-col gap-4 min-h-0">
            <NuxtLink to="/chats">
                <div class="flex items-center gap-6 p-4 border-[0.25px] border-gray-400 bg-white rounded-md">
                    <img src="~/assets/images/logo/Socles Logo.png" class="rounded-full" alt="">
                    <div class="hidden md:block">
                        <h3 class="font-medium text-lg text-neutral-800">Socles</h3>
                        <p class="text-xs text-neutral-500">UI/UX Designer</p>
                    </div>
                </div>
            </NuxtLink>
            <NuxtLink to="/chats">
                <div class="flex items-center gap-6 p-4 transition-all ease-in-out hover:bg-white rounded-md">
                    <img src="~/assets/images/logo/TW.png" class="rounded-full" alt="">
                    <div class="hidden md:block">
                        <h3 class="font-medium text-lg text-neutral-800">PT. Transfer Wawasan Indonesia</h3>
                        <p class="text-xs text-neutral-500">UI/UX Designer</p>
                    </div>
                </div>
            </NuxtLink>
            <NuxtLink to="/chats">
                <div class="flex items-center gap-6 p-4 transition-all ease-in-out hover:bg-white rounded-md">
                    <img src="~/assets/images/logo/Bitbybit.png" class="rounded-full" alt="">
                    <div class="hidden md:block">
                        <h3 class="font-medium text-lg text-neutral-800">Bitbybit</h3>
                        <p class="text-xs text-neutral-500">UI/UX Designer</p>
                    </div>
                </div>
            </NuxtLink>
        </div>
  
        <div class="p-6 flex-8/12 min-h-0">
            <slot />
        </div>
      </div>
    </div>
</template>  

<script setup>
import ChatHeader from './ChatHeader.vue';
</script>
