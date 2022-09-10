<script setup lang="ts">
import BathComp from "./icones/Bath.vue";
import HeartComp from "./icones/Heart.vue";
import type { SchemaOffreMaison } from "../types";
// interface SchemaOffreMaison {
//   id?: string; //TODO type uuid
//   /** nom du logement */
//   nom: string;
//   prix: number;
//   favori: boolean;
//   image: string;
//   /** nombre de lits du logement */
//   nbrLits: number;
//   /** nombre de salle de bain du logement */
//   nbrSDB: number;
//   // adresse: PostalAddress;
//   /** Surface habitable TODO: https://schema.org/floorSize ? */
//   // surface: string;
// }

defineProps<SchemaOffreMaison>();

// defineProps({
//   nom: String,
//   prix: Number,
//   favori: Boolean,
//   image: String, // les images sont simplement l'URL absolue (depuis la racine, débute par '/' )
//   nbrSDB: Number,
// });
</script>

<template>
  <div>
    <HeartComp />

    <BathComp />
  </div>
</template>
