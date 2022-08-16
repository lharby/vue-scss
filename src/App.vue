<template>
    <div id="app">
        <RetrieveProductData />
    </div>
</template>

<script>
    import RetrieveProductData from './components/RetrieveProductData.vue';

    export default {
        name: 'App',
        components: {
            RetrieveProductData,
        },
    };
</script>

<style lang="scss">
@import '../src/app/scss/main.scss';

#app {
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    color: $darkBlue;
    margin-top: 60px;
}
</style>
