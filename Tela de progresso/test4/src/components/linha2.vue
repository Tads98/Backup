<template>
    <div class="container3">
        <div class="ex">
        <img src="..\assets\more.png" />
        Exame Extra-Oral</div>
        <div class="ex2">
        <img src="..\assets\more.png" />
        Intercorrência</div>
        <div class="ex3">
        <img src="..\assets\more.png" />
        Exame Intra-Oral (Pós)</div>
        <div class="ex4">
        <img src="..\assets\more.png" />
        Exame Intra-Oral (Pré)
    </div>
    </div>    
</template>

<script>
export default {
    name: 'linha2',
    props: ["linha2"]
}
</script>

<style scoped>
.ex {
    position: absolute;
    width: 370px;
    height: 50px;
    left: 500px;
    top: 400px;
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

.ex2{
    position: absolute;
    width: 370px;
    height: 50px;
    left: 500px;
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

.ex3{
    position: absolute;
    width: 370px;
    height: 50px;
    left: 500px;
    top: 560px;
    background: #FFFFFF;
    box-shadow: 0px 4px 8px orange;
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

.ex4{
    position: absolute;
    width: 370px;
    height: 50px;
    left: 500px;
    top: 640px;
    margin-bottom: 1cm;
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