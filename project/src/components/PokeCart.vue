<template>
   <div>
   
   <div>
        <img :src="Pack.img" alt="">
        <h2>{{ Pack.name }}</h2>
        <h4>{{ Pack.price }}</h4>
        <button @click="minus"> Remove from Cart</button>
    </div>
</div>
    <h1>Total Items </h1>
</template>

<script setup>
import "./PokeCard.vue"
import { ref } from "vue";

const clicked = ref(0);
function minus(){
    clicked.value--;
}
</script>

<style scoped>

</style>