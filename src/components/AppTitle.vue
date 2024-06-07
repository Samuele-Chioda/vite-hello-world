<template>
    <!-- Qui va il markup HTML del tuo componente -->
    <div>
        <h1>La mia prima volta con Vite</h1>
        <!-- Contenuto del componente -->
    </div>
</template>

<script setup>
  // Qui va la logica del tuo componente
  // Importa qualsiasi dipendenza necessaria
  import { ref } from 'vue'; // Esempio di importazione di una funzione di composizione

  // Definisci le proprietà del componente, se necessario
  // defineProps({})

  // Definisci gli stati reattivi, funzioni e qualsiasi altra logica
const state = ref(0);
</script>

<style scoped>

body{
  background-color: black;
}

h1{
    background-color: lightblue;
    text-shadow: black;
    font-size: 2rem;
    padding: 1rem;
}
  /* Qui va lo stile CSS del tuo componente */
div {
    /* Esempio di stile */
    color: #42b983;
}
</style>
