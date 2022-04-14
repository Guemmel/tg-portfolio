<template>
    <div class="flex justify-between mb-24">
        <router-link to="/" class="text-3xl">{{ name }}</router-link>
        <div class="space-x-6">
            <router-link to="/about" :class="{underline: $route.name === 'about'}">About</router-link>
            <a :href="`https://www.instagram.com/${insta}/`" target="_blank">Instagram</a>
        </div>
    </div>

    <p class="text-4xl max-w-md mb-12">{{ description }}</p>
</template>

<script setup>
defineProps({
    name: String,
    insta: String,
    description: String,
})
</script>