<script>
export default {
    name: 'AppHeader',
    props: {
        sections: Array
    }
}
</script>


<template>
    <div class="container">
        <img src="@/assets/img/dc-logo.png" alt="Logo dc">

        <ul>
            <li v-for="(section, i) in sections" :key="i">{{ section.text }}</li>
        </ul>
    </div>
</template>

<style lang="scss" scoped>
div.container {
    background-color: white;
    padding: 1rem 0 1rem 0;
    display: flex;
    justify-content: space-around;
    align-items: center;

    ul {
        display: flex;
        align-items: center;
        gap: 1rem;

        li {
            font-weight: bold
        }
    }
}
</style>