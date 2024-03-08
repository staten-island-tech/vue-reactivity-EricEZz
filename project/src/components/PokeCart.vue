<template>
   <div class="cart">
   <h1>Cart</h1>
   <div
   v-for="pack in props.cart"
   :key="pack.name"
   class="cartInfo">
        <img :src="pack.img" alt="">
        <h2>{{ pack.name }}</h2>
        <h3>{{ pack.img }}</h3>
        <h4>{{ pack.price }}</h4>
    </div>
    <div> 
        <h2 class="total"> Total = ${{ props.total }}</h2>
    </div>
</div>
</template>

<script setup>
import{defineProps} from "vue";

const props = defineProps({ cart: Array, total: Number })

// import "./PokeCard.vue"
// import { ref } from "vue";

// const clicked = ref(0);
// function minus(){
//     clicked.value--;
// }
</script>

<style scoped>

</style>