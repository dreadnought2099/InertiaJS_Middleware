<script setup>
import { ref } from "vue";

const message = ref("This is an emergency!");
</script>

<template>
    <h1>Inertia JS</h1>
    <p>{{ message }}</p>
</template>
