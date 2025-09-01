<script setup>
import ContactUs from '@/components/ContactUs.vue';
import ButtonCounter from '@/components/ButtonCounter.vue';

const message = "Hello from Vue"
</script>

<template>
    <h1>{{ message }}</h1>

    <ContactUs />
    <ButtonCounter />
</template>