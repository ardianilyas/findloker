<template>
    <div class="flex flex-col-reverse md:flex-row items-center justify-between gap-4 min-h-fit">
        <div class="space-y-2 text-center md:text-left">
            <h1 class="text-5xl md:text-6xl font-medium">Find a job that suits your interest & skills.</h1>
            <NuxtLink to="/" class="mt-6 flex items-center gap-2">
                <Input placeholder="Search for job..." class="w-full flex-3/5 md:flex-5/5" />
                <Button class="flex-2/5">Search a job</Button>
            </NuxtLink>
            <p class="text-neutral-600 text-sm font-light">Popular : UI Designer, UX Researcher, Software Engineer, Admin</p>
        </div>
        <div class="flex justify-center items-center">
            <img class="w-9/12" src="../assets/images/hero.png" alt="">
        </div>
    </div>

    <section class="my-12">
        <div class="flex justify-between items-center">
            <h2 class="font-medium text-3xl">Explore by <span class="text-blue-400">category</span></h2>
            <NuxtLink to="/" class="flex gap-3 items-center text-neutral-500 font-light">
                Show all jobs
                <MoveRight />
            </NuxtLink>
        </div>
        <div class="my-8 grid grid-cols-1 sm:grid-cols-3 md:grid-cols-4 gap-4">
            <CategoryCard>
                <Laptop class="w-12 h-12 text-blue-800" />
                <h3 class="font-medium text-xl mt-2">Software Engineer</h3>
                <p class="text-neutral-600 font-light flex gap-3">
                    120 Jobs 
                    <MoveRight />
                </p>
            </CategoryCard>
            <CategoryCard>
                <Megaphone class="w-12 h-12 text-blue-800" />
                <h3 class="font-medium text-xl mt-2">Marketing</h3>
                <p class="text-neutral-600 font-light flex gap-3">
                    320 Jobs
                    <MoveRight />
                </p>
            </CategoryCard>
            <CategoryCard>
                <Banknote class="w-12 h-12 text-blue-800" />
                <h3 class="font-medium text-xl mt-2">Finance</h3>
                <p class="text-neutral-600 font-light flex gap-3">
                    279 Jobs
                    <MoveRight />
                </p>
            </CategoryCard>
            <CategoryCard>
                <PencilRuler class="w-12 h-12 text-blue-800" />
                <h3 class="font-medium text-xl mt-2">Design</h3>
                <p class="text-neutral-600 font-light flex gap-3">
                    189 Jobs
                    <MoveRight />
                </p>
            </CategoryCard>
        </div>
    </section>
</template>

<script setup lang="ts">
import { Laptop, Megaphone, Banknote, PencilRuler, MoveRight } from 'lucide-vue-next'
</script>