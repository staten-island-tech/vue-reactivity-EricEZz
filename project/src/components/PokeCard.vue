<template>
    <div class="cards">
        <h2 class="name">{{ Pack.name }}</h2>
        <img :src="Pack.img" alt="" class="img">
        <h4 class="desc">{{ Pack.price }}</h4>
        <button id="btn" @click="addToCart()"> Add to Cart</button>
    </div>
</template>

<script setup>
const props = defineProps({
    Pack:Object,
}); 

const emit = defineEmits([
    "add"
])
function addToCart(){
    emit("add")
}


</script>

<style scoped>

img{
width: 250px;
height: 450px;
object-fit: cover;
}</style>
