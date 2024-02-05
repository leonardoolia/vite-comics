<script>
import ProductCard from './products/ProductCard.vue';
export default {
    name: 'MainTop',
    props: {
        products: Array
    },
    components: { ProductCard }
}
</script>

<template>
    <main>
        <section id="series">
            <div class="container card-container">
                <ProductCard v-for="(product, i) in products" :key="i" :product="product" />
            </div>
        </section>
    </main>
</template>

<style lang="scss" scoped>
#series {
    color: white;
    background-color: #1c1c1c;
    min-height: 50px;
    display: flex;
    align-items: center;
    justify-content: center;
    padding: 1rem 0 1rem 0;

    .card-container {
        display: flex;
        flex-wrap: wrap;

        .product-card {
            flex-basis: calc(100% / 6)
        }
    }
}
</style>