<template>
    <NuxtLink to="/jobs/detail">
        <div class="p-6 bg-white hover:bg-gray-50 transition-all ease-in-out border-[0.5px] border-gray-300 rounded-md shadow-md space-y-2">
            <h4 class="text-xl font-medium"> {{ title }} </h4>
            <div class="flex items-center gap-3">
                <p class="text-[10px] font-medium uppercase text-green-800 bg-green-200 px-2 py-1 rounded-sm inline-flex"> {{ type }} </p>
                <p class="text-sm text-neutral-500">IDR {{ salary }} / month </p>
            </div>
            <div class="flex justify-between items-center">
                <div class="flex gap-4 items-center">
                    <img :src="logoSrc" alt="company logo" class="w-10 h-10 rounded-full" />
                    <div>
                        <p class="font-medium"> {{ company }} </p>
                        <div class="flex items-center gap-1">
                            <MapPin class="w-4 h-4 text-neutral-500" />
                            <p class="text-sm text-neutral-500"> {{ location }} </p>
                        </div>
                    </div>
                </div>
                <button class="cursor-pointer">
                    <Bookmark class="w-6 h-6 text-neutral-400" />
                </button>
            </div>
        </div>
    </NuxtLink>
</template>

<script setup>
import { MapPin, Bookmark } from 'lucide-vue-next'

const props = defineProps({
    title: String,
    image: String,
    company: String,
    location: String,
    type: String,
    salary: String,
});

const logoSrc = new URL(`../assets/images/logo/${props.image}`, import.meta.url).href;

</script>