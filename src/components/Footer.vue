<template>
    <div class="bg-orange-100 h-64 flex items-center justify-start space-x-40">
        <h1 class="pl-12 text-2xl">{{ name }}</h1>
        <span class="mt-5">
            <a :href="`mailto:${mail}`">{{ mail }}</a>
            <br>
            <span>Follow on <a class="underline" :href="`https://www.instagram.com/${insta}/`"
                    target="_blank">Instagram</a></span>
        </span>
    </div>
</template>

<script setup>
defineProps({
    name: String,
    mail: String,
    insta: String,
})
</script>

<style>
</style>