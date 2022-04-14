<template>
  <div class="m-11">
    <NavbarVue :name="full_name" :insta="insta_account"
      description="Preisgekrönter Kokser, Paul ist der Beste mit Sitz in Deutschland." />
    <router-view></router-view>
  </div>
  <FooterVue :name="full_name" mail="sample@gmail.com" :insta="insta_account" />

</template>

<script setup>
import NavbarVue from './components/Navbar.vue';
import FooterVue from './components/Footer.vue';

const full_name = 'Max Mustermann';
const insta_account = 'sample';
</script>