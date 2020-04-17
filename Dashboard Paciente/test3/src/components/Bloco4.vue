<template>
    <div class="retangulo4">
        <div class="linha2"></div>
            <h1 class="p9">Informações de Saúde</h1>
            <ul class="p10">
            <li>Diabetes tipo 1</li>
            <li>Gestante: 6 semanas</li>
            <li>Alérgia à: Dípirona e Paracetamol</li>
            <li>Insuficiência Cardíaca</li>
            </ul>
    </div>
</template>

<script>
export default {
    name: 'Bloco4',
    props: ["Bloco4"]
}    
</script>

<style scoped>
.retangulo4 {
    position: absolute;
    width: 620px;
    height: 315px;
    left: 1027px;
    top: 290px;
    margin-left: -90mm;
    margin-bottom: 5mm;

    background: #FFFFFF;
    box-shadow: 1px 8px 25px rgba(0, 0, 0, 0.15);
    border-radius: 15px;
}

.linha2{
    height: 280px;
    border-left: 2.5px solid rgba(149, 149, 149, 0.5);
    margin-left: 50px;
    margin-top: 0.5cm;
}

.p9 {
    position: absolute;
    width: 475.73px;
    height: 46px;
    left: 100px;
    top: -1px;

    font-family: Titillium Web;
    font-style: normal;
    font-weight: bold;
    font-size: 30px;
    line-height: 46px;
    
    color: #679C9A;
    display: flex;
    align-items: center;
}

.p10 {
    position: absolute;
    width: 475.73px;
    height: 46px;
    left: 100px;
    top: 80px;

    font-family: Titillium Web;
    font-style: normal;
    font-weight: bold;
    font-size: 25px;
    line-height: 46px;
}

</style>