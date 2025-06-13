<template>
    <div class="flex flex-col md:flex-row gap-4 justify-between md:items-center">
        <div class="flex gap-4 items-center">
            <img class="w-16 h-1w-16 rounded-full" src="~/assets/images/logo/Socles Logo.png" alt="Socles Logo">
            <div class="space-y-1">
                <h2 class="text-2xl text-neutral-800 font-bold">UI/UX Designer</h2>
                <div class="flex gap-2 items-center">
                    <p>at Socles</p>
                    <p class="text-[10px] font-medium uppercase text-green-800 bg-green-200 px-2 py-1 rounded-sm inline-flex"> Full Time </p>
                </div>
            </div>
        </div>
        <div class="flex gap-2">
            <ButtonSecondary class="">
                <Bookmark class="w-6 h-6 text-blue-500" />
            </ButtonSecondary>
            <Button class="px-10">
                Apply Now
                <MoveRight class="w-6 h-6" />
            </Button>
        </div>
    </div>
    <div class="my-12 flex flex-col md:flex-row gap-8 text-justify">
        <div class="basis-6/12">
            <h2 class="text-lg font-medium text-neutral-800">Job Description :</h2>
            <p class="my-2 text-neutral-600 font-light">Socles Membuka Kesempatan untuk Posisi UI/UX Designer! 📢Anda tertarik mengembangkan sistem dan aplikasi baru untuk klien-klien fleet besar di seluruh Indonesia? Bergabunglah bersama Socles. Di sini Anda akan berperan merancang tampilan dan pengalaman user yang intuitif, bersih, dan powerful. Dengan pengalaman lebih dari 8 tahun, Socles telah dipercaya oleh lebih dari 10.000 armada di seluruh Indonesia. Kami bekerja sama dengan lebih dari 200 mekanik yang tersebar di kabupaten dan kota di Indonesia untuk memastikan armada customer selalu dalam kondisi optimal. Socles menjadi pemanar menuju pemimpin teknologi IoT yang terpercaya di Indonesia. Kami percaya, berkarya dengan kerja cerdas, membuat kami bisa semakin berdampak optimal bagi para pemilik armada di industri transportasi, perkebunan, dan pertambangan.</p>

            <h2 class="text-lg font-medium text-neutral-800">What will you do :</h2>
            <ul class="my-2 mx-10 text-neutral-600 font-light">
                <li class="list-disc">Merancang alur dan tampilan aplikasi (wireframe hingga high-fidelity) menggunakan Figma.</li>
                <li class="list-disc">Melakukan user research, benchmarking, dan usability testing untuk memahami kebutuhan pengguna.</li>
                <li class="list-disc">Bekerja sama dengan tim produk dan developer dalam proses iterasi desain.</li>
                <li class="list-disc">Menyusun dan memelihara design system yang konsisten dan mudah digunakan.</li>
            </ul>

            <h2 class="text-lg font-medium text-neutral-800">Requirements :</h2>  
            <ul class="my-2 mx-10 text-neutral-600 font-light">
                <li class="list-disc">Pendidikan minimal D3/S1 bidang desain atau relevan, dengan portofolio UI/UX.</li>
                <li class="list-disc">Mahir menggunakan Figma untuk wireframing, prototyping, dan komponen desain.</li>
                <li class="list-disc">Teliti, memiliki attention to detail, dan paham prinsip desain antarmuka serta design thinking.</li>
                <li class="list-disc">Mampu bekerja kolaboratif, menerima feedback, dan komunikasi visual/verbal yang baik.</li>
            </ul>

            <h2 class="text-lg font-medium text-neutral-800">Benefits :</h2>
            <ul class="my-2 mx-10 text-neutral-600 font-light">
                <li class="list-disc">Competitive Salary</li>
                <li class="list-disc">Supportive Work Environment</li>
                <li class="list-disc">Training dan Coaching pengembangan diri</li>
                <li class="list-disc">Quarterly Team Celebration & Annual Rewards Holiday Trip.</li>
                <li class="list-disc">Annual Bonus: berdasarkan company & individual performance.</li>
            </ul>
            
        </div>
        <div class="basis-6/12">
            <div class="flex flex-col md:flex-row gap-8 p-6 justify-center items-center text-center border border-blue-200 rounded-lg">
                <div class="px-8 basis-1/2">
                    <p class="text-lg font-medium ">Salary (IDR)</p>
                    <p class="text-green-500">4.500.000 - 6.500.000</p>
                    <p class="text-neutral-500 font-light">per month</p>
                </div>
                <div class="w-3/4 h-[1px] md:w-2 md:h-full bg-blue-200"></div>
                <div class="basis-1/2 px-8">
                    <Map class="flex justify-center h-10 w-full text-blue-500" />
                    <h5 class="text-xl font-medium">Job Location</h5>
                    <p class="text-neutral-500 font-light">Setiabudi, Jakarta Selatan, DKI Jakarta</p>
                </div>
            </div>
            <div class="mt-6 flex flex-col gap-4 p-6 border border-blue-200 rounded-lg text-left">
                <h4 class="text-xl font-medium text-neutral-800">Job Overview</h4>
                <div class="grid grid-cols-2 md:grid-cols-3 gap-6">
                    <div class="flex flex-col">
                        <Calendar class="mb-2 w-8 h-8 text-blue-700" />
                        <p class="text-neutral-500 font-light uppercase">Job Posted : </p>
                        <p class="font-medium text-neutral-800">13 Jun 2025 </p>
                    </div>
                    <div class="flex flex-col">
                        <Timer class="mb-2 w-8 h-8 text-blue-700" />
                        <p class="text-neutral-500 font-light uppercase">Job Expire In : </p>
                        <p class="font-medium text-neutral-800">13 Jul 2025 </p>
                    </div>
                    <div class="flex flex-col">
                        <Layers class="mb-2 w-8 h-8 text-blue-700" />
                        <p class="text-neutral-500 font-light uppercase">Job Level : </p>
                        <p class="font-medium text-neutral-800">Entry Level </p>
                    </div>
                    <div class="flex flex-col">
                        <Briefcase class="mb-2 w-8 h-8 text-blue-700" />
                        <p class="text-neutral-500 font-light uppercase">Expreience : </p>
                        <p class="font-medium text-neutral-800">0 - 1 year of experience</p>
                    </div>
                    <div class="flex flex-col">
                        <GraduationCap class="mb-2 w-8 h-8 text-blue-700" />
                        <p class="text-neutral-500 font-light uppercase">Education : </p>
                        <p class="font-medium text-neutral-800">Bachelor Degree</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script setup>
import { Bookmark, MoveRight, Map, Calendar, Timer, Layers, Briefcase, GraduationCap } from 'lucide-vue-next'
</script>