<template>
    <div>
        <h1 class="text-2xl font-semibold text-neutral-800">Job For UI/UX Designer</h1>
        <!-- Form section -->
        <div class="flex flex-col md:flex-row gap-3 my-6 p-2 border border-[#4640DE] rounded-md">
            <Input placeholder="Search" />
            <Input placeholder="City" />
            <ButtonSecondary>
                <SlidersVertical />
                Filters
            </ButtonSecondary>
            <Button class="basis-1/6">Find Job</Button>
        </div>
        <!-- Job list section -->
         <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-4">
            <div v-for="job in jobs" :key="job.id">
                <JobCard :title="job.title" :type="job.type" :salary="job.salary" :image="job.image" :company="job.company" :location="job.location" />
            </div>
         </div>
    </div>
</template>

<script setup lang="ts">
import { SlidersVertical } from 'lucide-vue-next'
import { jobsData } from '@/data/jobs'

const jobs = jobsData;
</script>