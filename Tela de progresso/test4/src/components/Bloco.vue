<template>
    <div class="container">
        <h1 class="titulo">Nível de Progresso dos Documentos do Prontuário</h1>
            <p class="text">Documentos Concluídos</p>
            <p class="text4">75%</p>
            <i class="grey"></i>
            <i class="green"></i>
            <p class="text2">Documentos Pendentes</p>
            <p class="text5">30%</p>
            <i class="grey2"></i>
            <i class="red"></i>
            <p class="text3">Documentos em Andamento</p>
            <p class="text6">50%</p>
            <i class="grey3"></i>
            <i class="yellow"></i>
    </div>
</template>

<script>
export default {
    name: 'Bloco',
    props: ["Bloco"]        
}
</script>

<style scoped>
.container {
    position: absolute;
    width: 1250px;
    height: 330px;
    left: 65px;
    top: 90px;
    margin-top: -10mm;

    background: #FFFFFF;
    box-shadow: 0px 4px 25px rgba(0, 0, 0, 0.15);
    border-radius: 15px;
}

h1.titulo {
    position: absolute;
    width: 535px;
    height: 46px;
    left: 55px;
    top: -10px;

    font-family: Titillium Web;
    font-style: normal;
    font-weight: bold;
    font-size: 21px;
    line-height: 46px;


    display: flex;
    align-items: center;
    letter-spacing: 0.05em;

    color: #679C9A;
}

.text{
    position: absolute;
    width: 375.9px;
    height: 27px;
    left: -320px;
    top: 45px;
    margin-left: 10cm;

    font-family: Titillium Web;
    font-style: normal;
    font-weight: normal;
    font-size: 18px;
    line-height: 27px;
    display: flex;
    align-items: center;

    color: #353535;
}

.text4{
    position: absolute;
    width: 375.9px;
    height: 27px;
    left: 755px;
    top: 75px;
    margin-left: 10cm;

    font-family: Titillium Web;
    font-style: normal;
    font-weight: normal;
    font-size: 18px;
    line-height: 27px;
    display: flex;
    align-items: center;

    color: #353535;
}

.grey {
    position: absolute;
    width: 1060px;
    height: 20px;
    left: 55px;
    top: 100px;

    background: #C4C4C4;
    border-radius: 100px;
}

.green{
    position: absolute;
    width: 780px;
    height: 20px;
    left: 55px;
    top: 100px;

    background: #03A400;
    border-radius: 100px;
}

.text2{
    position: absolute;
    width: 375.9px;
    height: 27px;
    left: -320px;
    top: 120px;
    margin-left: 10cm;

    font-family: Titillium Web;
    font-style: normal;
    font-weight: normal;
    font-size: 18px;
    line-height: 27px;
    display: flex;
    align-items: center;

    color: #353535;
}

.text5{
    position: absolute;
    width: 375.9px;
    height: 27px;
    left: 755px;
    top: 150px;
    margin-left: 10cm;

    font-family: Titillium Web;
    font-style: normal;
    font-weight: normal;
    font-size: 18px;
    line-height: 27px;
    display: flex;
    align-items: center;

    color: #353535;
}

.grey2 {
    position: absolute;
    width: 1060px;
    height: 20px;
    left: 55px;
    top: 175px;

    background: #C4C4C4;
    border-radius: 100px;
}

.red{
    position: absolute;
    width: 175px;
    height: 20px;
    left: 55px;
    top: 175px;

    background: #BD2130;
    border-radius: 100px;
}

.text3{
    position: absolute;
    width: 375.9px;
    height: 27px;
    left: -320px;
    top: 195px;
    margin-left: 10cm;

    font-family: Titillium Web;
    font-style: normal;
    font-weight: normal;
    font-size: 18px;
    line-height: 27px;
    display: flex;
    align-items: center;

    color: #353535;
}

.text6{
    position: absolute;
    width: 375.9px;
    height: 27px;
    left: 755px;
    top: 226px;
    margin-left: 10cm;

    font-family: Titillium Web;
    font-style: normal;
    font-weight: normal;
    font-size: 18px;
    line-height: 27px;
    display: flex;
    align-items: center;

    color: #353535;
}

.grey3 {
    position: absolute;
    width: 1060px;
    height: 20px;
    left: 55px;
    top: 250px;

    background: #C4C4C4;
    border-radius: 100px;
}

.yellow{
    position: absolute;
    width: 250px;
    height: 20px;
    left: 55px;
    top: 250px;

    background: #FF9929;
    border-radius: 100px;
}
</style>