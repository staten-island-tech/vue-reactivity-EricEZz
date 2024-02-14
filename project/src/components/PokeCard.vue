<template>
    <div>
        <h2>{{ Pack.name }}</h2>
        <img :src="Pack.img" alt="">
        <h3>{{ Pack.gen }}</h3>
        <button>Add to Cart</button>
    </div>
</template>

<script setup>
 import { ref } from "vue";
const props = defineProps({
    //age:Number
    Pack: Object,
});
const clicked = ref(0);
function increment(){
    clicked.value++;
}
</script>

<style scoped>

img{
width: 250px;
height: 300px;
object-fit: cover;
}
</style>