<template>
    <div class="cart">
        <h2 class="">Cart:</h2>
        <div
        v-for="pack in props.cart"
        :key= "pack.name">
    <h2>{{ pack.name }}</h2>
    <h3>{{ pack.img }}</h3>
    <h4>{{ pack.price }}</h4>
    </div>
    </div>
</template>

<script>

</script>

<style scoped>

</style>