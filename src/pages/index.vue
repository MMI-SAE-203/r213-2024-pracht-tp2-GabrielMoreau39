<script setup lang="ts">
import MaisonCard from '@/components/MaisonCard.vue'
import { pb } from '@/backend';
const maisonsListe = await pb.collection('maison').getFullList({ filter:'favori=true', });

</script>

<template>
 
    <h1 class="text-2xl">Bonjour monde !</h1>
    <MaisonCard v-for="uneMaison in maisonsListe" :key="uneMaison.id" 
    v-bind="uneMaison" />
</template>
