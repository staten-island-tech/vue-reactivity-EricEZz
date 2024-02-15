<template>
  <div>
    <PokeCard v-for="pack in packs" 
    :key="pack.name" 
    :Pack="pack"/>
    <button></button>
  </div>
</template>

<script setup>
import PokeCard from "@/components/PokeCard.vue";
const packs = [
        {
          name: "Scarlet and Violet Booster Pack",
          price:4.99,
          gen:"Scarlet and Violet",
          img:"https://product-images.tcgplayer.com/fit-in/437x437/476451.jpg"
        },
        {
         name:"Paradox Rift Booster Pack",
         price:4.99,
         gen:"",
         img:"https://product-images.tcgplayer.com/fit-in/437x437/512822.jpg"
        },
        {
          name:" Sword & Shield - Silver Tempest Booster Pack",
          price:4.99,
          gen:"",
          img:"https://cdn.shoplightspeed.com/shops/638019/files/50319431/660x660x2/pokemon-pokemon-tcg-booster-pack-individual-sword.jpg"
        },
        {
          name:"Pokemon Sword & Shield: Vivid Voltage Booster Pack",
          price:3.99,
          gen:"Sword & Shield",
          img:"https://product-images.tcgplayer.com/fit-in/437x437/221312.jpg"
        },
        {
         name:"Crown Zenith Booster Pack",
         price:3.74,
         gen:"Sword & Shield",
         img:"https://product-images.tcgplayer.com/fit-in/437x437/453466.jpg"
        },
        {
          name:"Sword & Shield - Darkness Ablaze Booster Pack",
          price:7.37,
          gen:"Sword & Shield",
          img:"https://product-images.tcgplayer.com/fit-in/437x437/216852.jpg"
        },
      ]
</script>

<style scoped>
</style>