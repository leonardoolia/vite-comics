<script>
export default {
    name: 'ProductCard',
    props: {
        product: Object
    }
}
</script>

<template>
    <div class="product-card">
        <img :src="product.thumb" :alt="product.series">
        <h4>{{ product.series }}</h4>
    </div>
</template>

<style lang="scss" scoped>
.product-card {
    margin-bottom: 1rem;
    padding-top: 1rem;
    text-align: center;


    img {
        width: 100px;
        height: 100px;
        object-fit: cover;

    }
}
</style>