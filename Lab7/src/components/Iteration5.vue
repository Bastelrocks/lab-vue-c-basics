<script setup>
import { ref } from 'vue';

const backColor=ref("aqua");

const changeBackground=()=>{
    

}

</script>

<template>
<button class="cta" @click="changeBackground">Change Backgroundcolor</button>
</template>

<style scope>
*{
    background-color: backColor;
}
</style>