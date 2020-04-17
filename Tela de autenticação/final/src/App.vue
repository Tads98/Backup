<template>
    <div id="app">
        <final final/>
    </div>
</template>

<script>
    import final from './components/final.vue'

export default {
name: 'App',
components: {
    final
},
    props: ["final"]
}
</script>

<style>
#app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
}
</style>
