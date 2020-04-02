<template>
    <div class="odontograma">
        <div v-bind:key="dente.id" v-for="dente in dentes2">
            
            <img  v-bind:src='"../assets/Prancheta 2Dente "+dente.numero+".svg"' width="200" height="100">
            <h3>{{dente.numero}}</h3>
            <Esquema v-bind:esquema="esquemas" />
        </div>
    </div>
</template>

<script>
import Esquema from './Esquema';

export default {
    name: "Odontograma2",
    components: {
        Esquema
    },
    props: ["dentes2"]
}
</script>
<style lang="stylus" scoped>
.odontograma{
    width: 1000px;
    background-color : "#F1F2F3";
    display: flex;
    align-items: center;
    flex-direction: row-reverse;
    flex-wrap: wrap;
}
</style>