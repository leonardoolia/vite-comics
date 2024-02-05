<script>
import ProductCard from './products/ProductCard.vue';
export default {
    name: 'MainTop',
    props: {
        serie: Array
    },
    components: { ProductCard }
}
</script>

<template>
    <main>
        <section id="series">
            <div class="container card-container">
                <ProductCard v-for="(serie, i) in series" :key="i" :serie="serie" />
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

    .card-container {
        display: flex;
        flex-wrap: wrap;

        .product-card {
            flex-basis: calc(100% / 6)
        }
    }
}
</style>