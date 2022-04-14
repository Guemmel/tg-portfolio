<template>
    <div class="mb-12">
        <!--Add Images here!-->
        <p class="mt-12 max-w-xl text-2xl mb-6">{{ description }}</p>
        <a class="underline text-2xl" :href="project_url" target="_blank">Show Project &rarr;</a>
    </div>
</template>

<script setup>
defineProps({
    description: String,
    project_url: String,
})
</script>