<template>
    <div>
        <h2>{{ Pack.name }}</h2>
        <img :src="Pack.img" alt="">
        <h4>{{ Pack.price }}</h4>
        <button @click="increment"> Add to Cart</button>
        <ChildComp @response="(msg) => childMsg = msg"/>
    </div>
</template>

<script setup>
import ChildComp from "./PokeCart.vue"
const props = defineProps({
    //age:Number
    Pack: Object,
});
function increment(){

}
function add(){
   packs.push(pack)
}
</script>

<style scoped>

img{
width: 250px;
height: 450px;
object-fit: cover;
}</style>
