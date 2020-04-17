<template>
    <div class="container4">
        <div class="t">
        <img src="..\assets\more.png" />
        Odontograma</div>
        <div class="t2">
        <img src="..\assets\more.png" />
        Exames Complementares</div>
        <div class="t3">
        <img src="..\assets\more.png" />
        Plano de Tratamento</div>
        <div class="t4">
        Finalizar Prontuário
    </div>
    </div>    
</template>

<script>
export default {
    name: 'linha3',
    props: ["linha3"]
}
</script>

<style scoped>
.t {
    position: absolute;
    width: 380px;
    height: 50px;
    left: 935px;
    top: 400px;
    background: #FFFFFF;
    box-shadow: 0px 4px 8px green;
    border-radius: 15px;

    font-family: Titillium Web;
    font-style: normal;
    font-weight: normal;
    font-size: 25px;
    line-height: 46px;
    display: flex;
    align-items: initial;
    color: #353535;
}

.t2{
    position: absolute;
    width: 380px;
    height: 50px;
    left: 935px;
    top: 480px;
    background: #FFFFFF;
    box-shadow: 0px 4px 8px green;
    border-radius: 15px;

    font-family: Titillium Web;
    font-style: normal;
    font-weight: normal;
    font-size: 25px;
    line-height: 46px;
    display: flex;
    align-items: initial;
    color: #353535;
}

.t3{
    position: absolute;
    width: 380px;
    height: 50px;
    left: 935px;
    top: 560px;
    background: #FFFFFF;
    box-shadow: 0px 4px 8px red;
    border-radius: 15px;

    font-family: Titillium Web;
    font-style: normal;
    font-weight: normal;
    font-size: 25px;
    line-height: 46px;
    display: flex;
    align-items: initial;
    color: #353535;
}

.t4{
    position: absolute;
    width: 200px;
    height: 55px;
    left: 1110px;
    top: 630px;

    font-family: Titillium Web;
    font-style: normal;
    font-weight: normal;
    font-size: 24px;
    line-height: 37px;
    display: flex;
    align-items: center;
    text-align: center;

    color: #FFFFFF;

    background: #BD2130;
    border-radius: 5px;
}

img{
    position: absolute; 
    right: 3px; 
    top: -1px;
    margin-left: 10mm;
    margin-top: 1mm; 
    max-width: 200px;
    max-height: 200px;
    float: left;  
    padding: 5px 10px; 
    vertical-align: middle;   
}
</style>