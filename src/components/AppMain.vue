<script>
import MainTop from './MainTop.vue';
import MainBot from './MainBot.vue';

export default {
    name: 'AppMain',
    components: { MainTop, MainBot },
    props: {
        imgBot: String,
        textBot: String,
        serie: Array,
    }
}
</script>


<template>
    <MainTop :serie="serie" />
    <MainBot :img="imgBot" :text="textBot" />
</template>

<style lang="scss" scoped></style>