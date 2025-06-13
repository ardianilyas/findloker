<template>
    <div class="min-h-screen flex justify-center items-center lg:space-x-12 bg-gray-50 px-6 sm:px-10 md:px-12">
        <div class="w-full lg:flex-1/2 md:max-w-xl">
            <slot />
        </div>
        <div class="hidden lg:block flex-1/2">
            <img src="../assets/images/auth.png" alt="">
        </div>
    </div>
</template>

<script setup>

</script>