<template>
    <div>
        <img src="../assets/img/jumbotron.jpg" alt="">
    </div>
</template>

<script setup>
import { ref } from 'vue'; 
const state = ref(0);
</script>

<style scoped>

img{
    width: 100%;
    margin: 0 auto;
}
body{
    background-color: black;
}
</style>
