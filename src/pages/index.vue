<script setup lang="ts">
import type { MaisonRecord } from '@/types'
import MaisonCard from '@/components/MaisonCard.vue'
const maisonsListe:MaisonRecord[] = 
[
  {
    "adresse": "6 Rue des Gueux",
    "collectionId": "al8cjtcalaoox6q",
    "collectionName": "maison",
    "created": "2024-05-02 06:39:02.841Z",
    "favori": false,
    "id": "aryqncc017311ld",
    "image": "0000012647_16725_undefined_1606296794299_apMOjB6nx5.webp",
    "nbChambres": 2,
    "nbSdb": 1,
    "nomMaison": "Maison de gueux",
    "prix": 50000,
    "surface": 100,
    "updated": "2024-05-02 06:40:06.067Z"
  },
  {
    "adresse": "96 Rue de Toulouse",
    "collectionId": "al8cjtcalaoox6q",
    "collectionName": "maison",
    "created": "2024-05-02 06:38:01.267Z",
    "favori": false,
    "id": "wbxs5rcpfhrsqfl",
    "image": "decouvrez_les_50_plus_belles_maisons_de_vacances_en_france_dgq385Aftb.jpg",
    "nbChambres": 4,
    "nbSdb": 2,
    "nomMaison": "Maison de Vacances",
    "prix": 600000,
    "surface": 588,
    "updated": "2024-05-02 06:38:01.267Z"
  },
  {
    "adresse": "1 Rue St André",
    "collectionId": "al8cjtcalaoox6q",
    "collectionName": "maison",
    "created": "2024-05-02 06:36:40.383Z",
    "favori": true,
    "id": "n2jz2pqqlnwbc7o",
    "image": "adobe_stock_55289985_1280x855_ymGBn4TIF8.webp",
    "nbChambres": 3,
    "nbSdb": 1,
    "nomMaison": "Maison de Campagne",
    "prix": 400000,
    "surface": 500,
    "updated": "2024-05-02 06:36:40.383Z"
  },
  {
    "adresse": "1 Rue du Palais",
    "collectionId": "al8cjtcalaoox6q",
    "collectionName": "maison",
    "created": "2024-05-02 06:35:34.740Z",
    "favori": false,
    "id": "0p8c3ycmhq3s18z",
    "image": "31657927_29786447_Q6Vfa4bsru.jpg",
    "nbChambres": 5,
    "nbSdb": 6,
    "nomMaison": "Palais",
    "prix": 800000,
    "surface": 1000,
    "updated": "2024-05-02 06:35:34.740Z"
  },
  {
    "adresse": "1600 Pennsylvania Ave NW, Washington, DC 20500, États-Unis",
    "collectionId": "al8cjtcalaoox6q",
    "collectionName": "maison",
    "created": "2024-04-12 06:59:49.237Z",
    "favori": true,
    "id": "tulc0pz7aelxmmt",
    "image": "maison_blanche_Cgb4VyPUIg.jpg",
    "nbChambres": 18,
    "nbSdb": 19,
    "nomMaison": "Maison blanche",
    "prix": 1000000000,
    "surface": 2000,
    "updated": "2024-04-12 06:59:49.237Z"
  }
]

</script>

<template>
  <div>
    <h1 class="text-2xl">Bonjour monde !</h1>
    <MaisonCard v-bind="maisonsListe[2]" />
  </div>
</template>
