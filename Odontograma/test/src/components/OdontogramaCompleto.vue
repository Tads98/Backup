<template>
    <div>
        <Odontograma1 dentes1/>
        <Odontograma2 dentes2/>
        <Odontograma3 dentes3/>
        <Odontograma4 dentes4/>
    </div>
</template>

<script>
import Odontograma1 from './Odontograma1';
import Odontograma2 from './Odontograma2';
import Odontograma3 from './Odontograma3';
import Odontograma4 from './Odontograma4';

export default {
    name: "OdontogramaCompleto",
    components: {
        Odontograma1,
        Odontograma2,
        Odontograma3,
        Odontograma4
    },
    props: ["dentes1", "dentes2", "dentes3", "dentes4"]
}
</script>
<style lang="stylus" scoped>
.odontograma{
    background-color : "#F1F2F3";
    display: flex;
    align-items: center;
    flex-direction: row-reverse;
    flex-wrap: wrap;
}
</style>