<script setup>
import { ref } from "vue";
import "../../css/customFont.css";

const message = ref("This is an emergency!");
</script>

<template>
    <h1 class="outfit-custom2">Inertia JS</h1>
    <p class="outfit-custom">{{ message }}</p>
</template>
