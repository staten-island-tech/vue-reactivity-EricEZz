<template>
    <div>
        <h2>{{ Pack.name }}</h2>
        <img :src="Pack.img" alt="">
        <h3>Amount in Cart: {{ clicked }}</h3>
        <h4>{{ Pack.price }}</h4>
        <button @click="increment"> Add to Cart</button>
    </div>
</template>

<script setup>
import { ref } from "vue";
const props = defineProps({
    //age:Number
    Pack: Object,
});

//clicker logic 
const clicked = ref(0);
function increment(){
    clicked.value++;
}
</script>

<style scoped>

img{
width: 250px;
height: 450px;
object-fit: cover;
}</style>
