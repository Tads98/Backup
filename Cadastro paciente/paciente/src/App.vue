<template>
    <div id="app">
        <CadPaciente CadPaciente/>
    </div>
</template>

<script>
    import CadPaciente from './components/CadPaciente.vue'

export default {
name: 'App',
    components: {
    CadPaciente
},
    props: ["CadPaciente"]
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
