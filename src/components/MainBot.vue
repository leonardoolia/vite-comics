<script>
export default {
    name: 'MainBot',
    props: {
        img: String,
        text: String,
    },
    computed: {
        ImagePath() {
            const path = new URL(`../assets/img/${this.img}`, import.meta.url);
            return path.href;
        }
    }
}
</script>

<template>
    <ul>
        <li>
            <img :src="ImagePath" :alt="text">
        </li>
    </ul>
</template>

<style lang="scss" scoped></style>