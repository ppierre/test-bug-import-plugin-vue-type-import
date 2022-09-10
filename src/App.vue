<template>
  <h1>Test import</h1>
  <Card
    nom="test de nom"
    :prix="50"
    :favori="true"
    :nbrSDB="2"
    image="https://upload.wikimedia.org/wikipedia/commons/thumb/4/46/Epinal_Maison_Romaine.jpg/320px-Epinal_Maison_Romaine.jpg"
  />
</template>

<script setup lang="ts">
import Card from "./components/card.vue";
</script>
