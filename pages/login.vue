<template>
    <AuthLayout>
        <div class="bg-white p-8 rounded-lg shadow-md max-w-xl">
            <h1 class="text-2xl font-medium text-center mb-4">Login Findloker</h1>
            <form class="[&>div]:mb-4">
                <div>
                    <Label>Email</Label>
                    <Input placeholder="team@findloker.com" />
                </div>
                <div>
                    <Label>Password</Label>
                    <Input type="password" placeholder="*********" />
                </div>
                <div>
                    <p class="font-light text-sm">Dont have an account ? <NuxtLink to="/register" class="text-blue-500 hover:text-blue-600 transition-all ease-in-out underline underline-offset-4">Register</NuxtLink> </p>
                </div>
                <div>
                    <Button class="w-full">Login</Button>
                </div>
            </form>
        </div>
    </AuthLayout>
</template>

<script setup>
import AuthLayout from '~/components/AuthLayout.vue';
import Label from '~/components/Label.vue';

definePageMeta({
    layout: false
})
</script>