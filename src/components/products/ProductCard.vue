<script>
export default {
    name: 'ProductCard',
    props: {
        serie: Object
    }
}
</script>

<template>
    <div class="product-card">
        <img :src="serie.thumb" :alt="serie.series">
        <h4>{{ sere.series }}</h4>
    </div>
</template>

<style></style>