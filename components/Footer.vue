<script setup lang="ts">
import { Dribbble, Facebook, Instagram, Linkedin, Twitter } from 'lucide-vue-next';

</script>

<template>
    <footer class="px-8 sm:px-10 md:px-12 py-20 bg-[#4640DE] text-white">
        <div class="flex flex-col lg:grid lg:grid-cols-7 gap-8 font-light">
            <div class="col-span-3">
                <h4 class="text-xl font-semibold mb-4">Findloker</h4>
                <p class="text-lg">Great platform for the job seeker that passionate about startups. Find your dream job easier.</p>
            </div>
            <div class="col-span-1">
                <h4 class="font-semibold text-xl mb-4">About</h4>
                <ul class="flex flex-col gap-4">
                    <li>
                        <NuxtLink>Companies</NuxtLink>
                    </li>
                    <li>
                        <NuxtLink>Pricing</NuxtLink>
                    </li>
                    <li>
                        <NuxtLink>Terms</NuxtLink>
                    </li>
                    <li>
                        <NuxtLink>Advice</NuxtLink>
                    </li>
                    <li>
                        <NuxtLink>Privacy Policies</NuxtLink>
                    </li>
                </ul>
            </div>
            <div class="col-span-1">
                <h4 class="font-semibold text-xl mb-4">Reources</h4>
                <ul class="flex flex-col gap-4">
                    <li>
                        <NuxtLink>Help Docs</NuxtLink>
                    </li>
                    <li>
                        <NuxtLink>Guide</NuxtLink>
                    </li>
                    <li>
                        <NuxtLink>Updates</NuxtLink>
                    </li>
                    <li>
                        <NuxtLink>Contact Us</NuxtLink>
                    </li>
                </ul>
            </div>
            <div class="col-span-2">
                <h4 class="font-semibold text-xl mb-4">Get job notifications</h4>
                <p>The latest job news, articles, sent to your inbox weekly.</p>
            </div>
        </div>
        <div class="my-10 w-full border-t border-gray-400"></div>
        <div class="flex flex-col md:flex-row justify-start md:justify-between md:items-center gap-4">
            <p class="text-gray-200">2025 @ Findloker. All rights reserved.</p>
            <div class="flex gap-4">
                <div class="w-10 h-10 bg-gray-400/60 rounded-full flex justify-center items-center">
                    <Facebook />
                </div>
                <div class="w-10 h-10 bg-gray-400/60 rounded-full flex justify-center items-center">
                    <Instagram />
                </div>
                <div class="w-10 h-10 bg-gray-400/60 rounded-full flex justify-center items-center">
                    <Dribbble />
                </div>
                <div class="w-10 h-10 bg-gray-400/60 rounded-full flex justify-center items-center">
                    <Linkedin />
                </div>
                <div class="w-10 h-10 bg-gray-400/60 rounded-full flex justify-center items-center">
                    <Twitter />
                </div>
            </div>
        </div>
    </footer>
</template>