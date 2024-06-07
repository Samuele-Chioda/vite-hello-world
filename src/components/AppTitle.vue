<template>
    <!-- Qui va il markup HTML del tuo componente -->
    <div>
        <h1>La mia prima volta con Vite!</h1>
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

h1{
    background-color: black;
    text-shadow: 4px 4px 5px red;
    font-size: 2rem;
    padding: 1rem;
    color: yellowgreen;
}
  /* Qui va lo stile CSS del tuo componente */
</style>
