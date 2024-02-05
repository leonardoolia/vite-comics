<script>
import MainTop from './MainTop.vue';
import MainBot from './MainBot.vue';

export default {
    name: 'AppMain',
    components: { MainTop, MainBot },
    props: {
        imgBot: String,
        textBot: String,
        products: Array,
    }
}
</script>


<template>
    <MainTop :products="products" />
    <MainBot :img="imgBot" :text="textBot" />
</template>

<style lang="scss" scoped></style>