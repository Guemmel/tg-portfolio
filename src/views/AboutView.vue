<template>
  <div class="flex justify-center space-x-16">
    <div>
      <p class="max-w-xl mb-6">{{ description }}</p>

      <a class="underline" :href="`mailto:${mail}`">{{ mail }}</a>
      <br>
      <a class="underline" :href="`https://www.instagram.com/${insta}/`" target="_blank">Instagram</a>
    </div>
    <img src="https://picsum.photos/500/700" alt="">
  </div>
</template>

<script setup>
const description = 'Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.';
const mail = 'sample@mail.com'
const insta = 'sample'
</script>