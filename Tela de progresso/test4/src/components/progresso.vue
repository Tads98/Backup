<template>
  <div>
    <div class="title">
      <p>Petrus</p>
      </div>
      <hr class="bar">
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
        Exame Físico</div>
    </div>
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
        Exame Intra-Oral (Pré)</div>
    </div>
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
        Finalizar Prontuário</div>
    </div>

</div>

</template>

<script>
export default {
  name: 'progresso',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  @import url('https://fonts.googleapis.com/css?family=Titillium+Web&display=swap');

  .title {
  width: 134px;
  height: 28px;
  left: 893px;
  top: 14px;
  margin-left: 19.2em;

  font-family: 'Titillium Web', sans-serif;
  font-style: normal;
  font-weight: bold;
  font-size: 32px;
  line-height: 49px;
  display: flex;
  align-items: center;
  letter-spacing: 0.14em;

  color: #679C9A;
}

hr.bar{
  height: 10px;
  border: 0;
  box-shadow: 0 10px 10px -10px #8c8c8c inset;
}

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
  /* identical to box height */

  display: flex;
  align-items: center;
  letter-spacing: 0.05em;

  color: #679C9A;
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

.grey2 {
  position: absolute;
  width: 1060px;
  height: 20px;
  left: 55px;
  top: 175px;

  background: #C4C4C4;
  border-radius: 100px;
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

.green{
  position: absolute;
  width: 780px;
  height: 20px;
  left: 55px;
  top: 100px;

  background: #03A400;
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

.yellow{
  position: absolute;
  width: 250px;
  height: 20px;
  left: 55px;
  top: 250px;

  background: #FF9929;
  border-radius: 100px;
}

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
