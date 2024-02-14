<template>
  <div>
    <DestCard v-for="pack in packs" 
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
          img:"https://media.gamestop.com/i/gamestop/20002522_ALT01/Pokemon-Trading-Card-Game-Scarlet-and-Violet-Sleeved-Booster-Pack-Styles-May-Vary?$pdp$"

        },
        {
         name:"Paradox Rift Booster Pack",
         price:4.99,
         gen:"",
         img:"https://www.tcgpark.com/_next/image?url=https%3A%2F%2Fapi.tcgpark.com%2Fwp-content%2Fuploads%2F2023%2F08%2Fparadox-rift%E2%80%93booster-pack-2.jpg&w=640&q=75"

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
          img:"https://cdn.shoplightspeed.com/shops/638019/files/44898654/image.jpg"

        },
      ]
</script>

<style scoped>

</style>