<script setup>
import { ref } from 'vue';
const printString=ref("");

</script>

<template>
    <p>Mathematical Operation 2+2 = {{ 2+2 }}</p>
    <label for="string">String to be printed: </label>
    <input type="text" v-model="printString" id="string" placeholder="Enter a String">
    <p>{{ printString }}</p>
</template>

<style scoped>

</style>