<script setup>
import { ref } from 'vue';
const messege = ref('');
defineProps({
    label: String
});
</script>

<template>
    <span>{{ label }}</span>
    <input type="text" v-model="messege">
    <p>{{ messege }}</p>
</template>