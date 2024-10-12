<script setup>

const backColor=ref("aqua");

</script>

<template>
<button class="cta" @click="changeBackground">Change Backgroundcolor</button>
</template>

<style scope>
*{
    background-color: backColor;
}
</style>