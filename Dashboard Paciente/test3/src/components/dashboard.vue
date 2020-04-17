<template>
<div>
    <div class="title">
      <p>Petrus</p>
      </div>
      <hr class="new2">
      <div class="retangulo">
        <h1 class="titulo">Histórico de Tratamentos</h1>
        <table>
        <tr>
        <td>
          <div class="retangulo5">
            <a href="">
            <table>
              <div class="linha"></div>
              <tr>
              <td class="ex">
                <p>Nome do Exame</p>
              </td>
              <td class="ex1">
                <p>Dr. Nome do Dentista</p>
              </td>
              <td class="ex2">
                <li>Em aberto</li>
              </td>
              </tr>
            </table>
            </a>
          </div>
        </td>
        </tr>
        <tr>
        <td>
          <div class="retangulo6">
          <a href="">
          <table>
              <tr>
              <td class="ex">
                <p>Nome do Exame</p>
              </td>
              <td class="ex1">
                <p>Dr. Nome do Dentista</p>
              </td>
              <td class="ex2">
                <li>Em aberto</li>
              </td>
              </tr>
            </table>
            </a>
          </div>
        </td>
        </tr>
        <tr>
        <td>
          <div class="retangulo7">
          <a href="">
          <table>
              <tr>
              <td class="ex">
                <p>Nome do Exame</p>
              </td>
              <td class="ex1">
                <p>Dr. Nome do Dentista</p>
              </td>
              <td class="ex3">
                <li>Finalizado</li>
              </td>
              </tr>
            </table>
            </a>
          </div>
        </td>
        </tr>
        <tr>
        <td>
          <div class="retangulo8">
          <a href="">
          <table>
              <tr>
              <td class="ex">
                <p>Nome do Exame</p>
              </td>
              <td class="ex1">
                <p>Dr. Nome do Dentista</p>
              </td>
              <td class="ex4">
                <li>Cancelado</li>
              </td>
              </tr>
            </table>
            </a>
          </div>
        </td>
        </tr>
    </table>
      </div>
      <div class="retangulo2">
        <h1 class="titulo">Resumo do Tratamento Atual</h1>
        <p class="lorem">
          Lorem Ipsum is simply 
          dummy text of the printing and typesetting industry. 
          Lorem Ipsum has been the industry's standard dummy 
          text ever since the 1500s, when an unknown printer 
          took a galley of type and scrambled it to make a 
          type specimen book. It has survived not only five centuries,
          but also the leap into electronic typesetting, remaining 
          essentially unchanged. It was popularised in the 1960s 
          with the release of Letraset sheets containing Lorem Ipsum passages.
        </p>
        <p>
          <a href="" class="p">IR PARA O TRATAMENTO</a>
        </p>
      </div>
      <div class="retangulo3">
        <table>
          <tr>
            <td>
              <div class="retangulo9">
              </div>
            </td>
          </tr>
        </table>
        <p class="p1">PRESSÃO</p>
        <p class="p2">ALTURA</p>
        <p class="p3">MASSA C.</p>
        <p class="p4">14/9 mmHg</p>
        <p class="p5">1,70 m</p>
        <p class="p6">60 Kg</p>
        <p class="p7">Ana Maria Gomes</p>
        <p class="p8">30 Anos</p>
      </div>
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
</div>
</template>

<script>
export default {
  name: 'dashboard',
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

hr.new2{
  height: 10px;
  border: 0;
  box-shadow: 0 10px 10px -10px #8c8c8c inset;
}

.retangulo {
  position: absolute;
  width: 600px;
  height: 330px;
  left: 65px;
  top: 90px;
  margin-top: -10mm;

  background: #FFFFFF;
  box-shadow: 0px 4px 25px rgba(0, 0, 0, 0.15);
  border-radius: 15px;
}

.retangulo2 {
  position: absolute;
  width: 600px;
  height: 200px;
  left: 65px;
  top: 500px;
  margin-top: -25mm;
  margin-bottom: 5mm;

  background: #FFFFFF;
  box-shadow: 1px 8px 25px rgba(0, 0, 0, 0.15);
  border-radius: 15px;
}

.lorem {
  position: absolute;
  width: 510px;
  height: 50px;
  left: 30px;
  top: 60px;

  font-family: Titillium Web;
  font-style: normal;
  font-weight: 300;
  font-size: 13px;
  line-height: 13px;
  display: flex;
  align-items: center;
  letter-spacing: 0.05em;

  color: #656565;
}

.p {
  position: absolute;
  width: 233px;
  height: 30px;
  left: 30px;
  top: 130px;

  font-family: Titillium Web;
  font-style: normal;
  font-weight: 600;
  font-size: 15px;
  line-height: 30px;
  display: flex;
  align-items: center;
  letter-spacing: 0.05em;
  text-decoration-line: underline;

}
h1.titulo {
  position: absolute;
  width: 535px;
  height: 46px;
  left: 30px;
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

.retangulo3 {
  position: absolute;
  width: 620px;
  height: 210px;
  left: 1027px;
  top: 53px;
  margin-left: -90mm;
  

  background: #FFFFFF;
  box-shadow: 1px 4px 25px rgba(0, 0, 0, 0.15);
  border-radius: 15px;
}

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

.retangulo5 {
  position: absolute;
  width: 485px;
  height: 50px;
  left: 50px;
  top: 50px;
  cursor: pointer;
  background: #F4F4F4;
  box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.25);
  border-radius: 15px;
}

.retangulo6 {
  position: absolute;
  width: 485px;
  height: 50px;
  left: 50px;
  top: 120px;
  cursor: pointer;

  background: #F4F4F4;
  box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.25);
  border-radius: 15px;
}

.retangulo7 {
  position: absolute;
  width: 485px;
  height: 50px;
  left: 50px;
  top: 190px;
  cursor: pointer;

  background: #F4F4F4;
  box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.25);
  border-radius: 15px;
}

.retangulo8 {
  position: absolute;
  width: 485px;
  height: 50px;
  left: 50px;
  top: 255px;
  cursor: pointer;

  background: #F4F4F4;
  box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.25);
  border-radius: 15px;
}

.retangulo9 {
  position: absolute;
  width: 510px;
  height: 100px;
  left: 50px;
  top: 80px;

  border: 1px solid #909090;
  box-sizing: border-box;
  border-radius: 15px;
}

.p1{
  position: absolute;
  width: 132px;
  height: 46px;
  left: 80px;
  top: 70px;

  font-family: Titillium Web;
  font-style: normal;
  font-weight: normal;
  font-size: 20px;
  line-height: 30px;
  /* identical to box height */

  display: flex;
  align-items: center;
  text-align: center;
  letter-spacing: 0.05em;

  color: #00476B;
}

.p2 {
  position: absolute;
  width: 132px;
  height: 46px;
  left: 270px;
  top: 70px;

  font-family: Titillium Web;
  font-style: normal;
  font-weight: normal;
  font-size: 20px;
  line-height: 30px;
  /* identical to box height */

  display: flex;
  align-items: center;
  text-align: center;
  letter-spacing: 0.05em;

  color: #00476B;
}

.p3{
  position: absolute;
  width: 132px;
  height: 46px;
  left: 400px;
  top: 70px;

  font-family: Titillium Web;
  font-style: normal;
  font-weight: normal;
  font-size: 20px;
  line-height: 30px;
  /* identical to box height */

  display: flex;
  align-items: center;
  text-align: center;
  letter-spacing: 0.05em;

  color: #00476B;
}

.p4 {
  position: absolute;
  width: 132px;
  height: 46px;
  left: 85px;
  top: 110px;

  font-family: Titillium Web;
  font-style: normal;
  font-weight: normal;
  font-size: 15px;
  line-height: 46px;
  /* identical to box height */

  display: flex;
  align-items: center;
  text-align: center;

  color: #656565;
}

.p5 {
  position: absolute;
  width: 132px;
  height: 46px;
  left: 280px;
  top: 110px;

  font-family: Titillium Web;
  font-style: normal;
  font-weight: normal;
  font-size: 15px;
  line-height: 46px;
  /* identical to box height */

  display: flex;
  align-items: center;
  text-align: center;

  color: #656565;
}

.p6 {
  position: absolute;
  width: 132px;
  height: 46px;
  left: 425px;
  top: 110px;

  font-family: Titillium Web;
  font-style: normal;
  font-weight: normal;
  font-size: 15px;
  line-height: 46px;
  /* identical to box height */

  display: flex;
  align-items: center;
  text-align: center;

  color: #656565;
}

.p7{
  position: absolute;
  width: 132px;
  height: 46px;
  left: 250px;
  top: -5px;

  font-family: Titillium Web;
  font-style: normal;
  font-weight: 600;
  font-size: 14px;
  line-height: 25px;
  /* identical to box height */

  display: flex;
  align-items: center;
  text-align: center;
  text-decoration-line: underline;
}

.p8{
  position: absolute;
  width: 132px;
  height: 46px;
  left: 285px;
  top: 15px;

  font-family: Titillium Web;
  font-style: normal;
  font-weight: 600;
  font-size: 14px;
  line-height: 25px;
  /* identical to box height */

  display: flex;
  align-items: center;
  text-align: center;
  color: #353535;
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
  /* identical to box height */
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
  /* identical to box height */
  
}

.ex {
  position: absolute;
  width: 198px;
  height: 30px;
  left: 15px;
  top: 10px;

  font-family: Titillium Web;
  font-style: normal;
  font-weight: 600;
  font-size: 15px;
  line-height: 30px;
  display: flex;
  align-items: center;
  letter-spacing: 0.05em;

  color: #00476B;
}

.ex1 {
  position: absolute;
  width: 199px;
  height: 30px;
  left: 160px;
  top: 10px;

  font-family: Titillium Web;
  font-style: normal;
  font-weight: normal;
  font-size: 15px;
  line-height: 30px;
  display: flex;
  align-items: center;
  letter-spacing: 0.05em;

  color: #00476B;
}

.ex2 {
  position: absolute;
  width: 100px;
  height: 30px;
  left: 355px;
  top: 10px;

  font-family: Titillium Web;
  font-style: normal;
  font-weight: normal;
  font-size: 15px;
  line-height: 30px;
  display: flex;
  align-items: center;
  letter-spacing: 0.05em;
  color: #FF9929;
}

.ex3 {
  position: absolute;
  width: 199px;
  height: 30px;
  left: 355px;
  top: 10px;

  font-family: Titillium Web;
  font-style: normal;
  font-weight: normal;
  font-size: 15px;
  line-height: 30px;
  display: flex;
  align-items: center;
  letter-spacing: 0.05em;
  color: #03A400;
}

.ex4 {
  position: absolute;
  width: 199px;
  height: 30px;
  left: 355px;
  top: 10px;

  font-family: Titillium Web;
  font-style: normal;
  font-weight: normal;
  font-size: 15px;
  line-height: 30px;
  display: flex;
  align-items: center;
  letter-spacing: 0.05em;
  color: #BD2130;
}

.linha{
  height: 300px;/*Altura da linha*/
  border-left: 2.5px solid rgba(149, 149, 149, 0.5);/* Adiciona borda esquerda na div como ser fosse uma linha.*/
  margin-left: 510px;
  margin-top: -1cm;
}

.linha2{
  height: 280px;/*Altura da linha*/
  border-left: 2.5px solid rgba(149, 149, 149, 0.5);/* Adiciona borda esquerda na div como ser fosse uma linha.*/
  margin-left: 50px;
  margin-top: 0.5cm;
}

</style>
