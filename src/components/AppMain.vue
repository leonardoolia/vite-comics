<script>
import MainTop from './MainTop.vue';
import MainBot from './MainBot.vue';

export default {
    name: 'AppMain',
    components: { MainTop, MainBot }
}
</script>


<template>
    <MainTop />
    <MainBot />
</template>

<style lang="scss" scoped></style>