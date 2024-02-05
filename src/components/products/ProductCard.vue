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
img {
    width: 100px;
    height: auto;
}
</style>