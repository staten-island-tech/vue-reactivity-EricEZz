<template>
    <div>
        <h2>{{ pack.name }}</h2>
        <img :src="pack.img" alt="">
        <h3>{{ clicked }}</h3>
        <button @click="increment">Add to Cart</button>
    </div>
</template>

<script>

</script>

<style scoped>

</style>