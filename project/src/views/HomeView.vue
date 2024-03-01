<template>
  <div>
    <PokeCard v-for="pack in packs" 
    :key="pack.name" 
    :Pack="pack"/>
  </div>
</template>

<script setup>
import PokeCard from "@/components/PokeCard.vue";
import PokeCart from "@/components/Pokecart.vue";
const packs = [
        {
          name: "Scarlet and Violet Booster Pack",
          price:4.99,
          gen:"Scarlet & Violet",
          img:"https://product-images.tcgplayer.com/fit-in/437x437/476451.jpg"
        },
        {
         name:"Paradox Rift Booster Pack",
         price:4.99,
         gen:"Scarlet & Violet",
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
        {
          name:"Paldean Fates Booster Pack",
          price: 4.42,
          gen:"Scarlet & Violet",
          img: "https://product-images.tcgplayer.com/fit-in/437x437/528038.jpg"
        },
        {
          name:"Lost Origin Booster Pack",
          price:3.80,
          gen:"Sword & Shield",
          img:"https://product-images.tcgplayer.com/fit-in/437x437/277325.jpg"
        },
        {
          name:"Evolutions Booster Pack",
          price:22.74,
          gen:"XY",
          img:"https://product-images.tcgplayer.com/fit-in/437x437/129907.jpg"
        },
        {
          name:"Unbroken Bonds Booster Pack",
          price:15.89,
          gen:"Sun & Moon",
          img:"https://product-images.tcgplayer.com/fit-in/437x437/185718.jpg"
        },
        {
          name:"XY BREAKthrough Booster Pack",
          price:16.64,
          gen:"XY",
          img:"https://product-images.tcgplayer.com/fit-in/437x437/107666.jpg"
        },
        {
          name:"Next Destinies Booster Pack",
          price:69.98,
          gen:"Black & White",
          img:"https://product-images.tcgplayer.com/fit-in/437x437/98538.jpg"
        }
      ]
</script>

<style scoped>
</style>