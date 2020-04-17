<template>
    <div class="container2">
        <div class="new">
            <img src="..\assets\more.png" />
            Anamnese
            </div>
            <div class="new2">
            <img src="..\assets\more.png" />
            Receita</div>
            <div class="new3">
            <img src="..\assets\more.png" />
            Evolução</div>
            <div class="new4">
            <img src="..\assets\more.png" />
            Exame Físico
        </div>
    </div>
</template>

<script>
export default {
    name: 'linha1',
    props: ["linha1"]   
}
</script>

<style scoped>
.new {
    position: absolute;
    width: 380px;
    height: 50px;
    left: 70px;
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

.new2{
    position: absolute;
    width: 380px;
    height: 50px;
    left: 70px;
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

.new3{
    position: absolute;
    width: 380px;
    height: 50px;
    left: 70px;
    top: 560px;
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

.new4{
    position: absolute;
    width: 380px;
    height: 50px;
    left: 70px;
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