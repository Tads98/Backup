<template>
  <div id="app">    
  <OdontogramaCompleto /> 
      <div class="title">
      <p>Petrus</p>
      </div>
      <hr class="new2">
      <div>
      <table>
        <tr>
        <td>
          <div class="add">
          <p>Adicionar Odontograma</p>
          </div>
        </td>
        <td>
            <div>
                <a class="button" href="#">MINIMIZAR</a>
            </div>
        </td>
        <td>
            <div class="pointer">
                <a href="#">
                <img alt="seta" src="./assets/seta.png" width="25" height="25">
                </a>
             </div>
        </td>

        <td>
            <div>
                <a class="pointers" href="#">
                <img alt="Shadow" src="./assets/Shadow.png" width="25" height="25">
                </a>
                <a class="pointers2" href="#">
                <img alt="white" src="./assets/white.png" width="25" height="25">
                </a>
            </div>
        </td>

        <td>
            <div class="icons">
                
            </div>

            <div class="icons2">
            <a href="#">
               <img alt="dente" src="./assets/dente.png" width="30" height="30">
            </a>
            </div>

            <div class="icons3">
            <a href="#">
               <img alt="arcada-aberta" src="./assets/arcada-aberta.png" width="30" height="30">
            </a>
            </div>

            <div class="icons4">
            <a href="#">
               <img alt="arcada-fechada" src="./assets/arcada-fechada.png" width="30" height="30">
            </a>
            </div>

            <div class="logo">
            <a href="#">
               <img alt="Vector" src="./assets/Vector.png" width="30" height="30">
            </a>
            </div>
        </td>

        </tr>
    </table>
      </div>
      <hr class="new1">
      <div class="odontograma">
        <div class="q1"> 
          <div  v-bind:key="dente.id" v-for="dente in dentes1">
            
            <div class = "dentind">
            <img  v-bind:src='"./assets/Prancheta 2Dente "+dente.numero+".svg"' width="200" height="100" margin="0" padding="0">
            <h3 margin="0" padding="0">{{dente.numero}}</h3>
            <Esquema width="200" height="100" margin="0" padding="0"/>
            </div>
        </div>
        </div>
        <div class="q2"> 
          <div v-bind:key="dente.id" v-for="dente in dentes2">
            <div class = "dentind">
            <img  v-bind:src='"./assets/Prancheta 2Dente "+dente.numero+".svg"' width="200" height="100" margin="0" padding="0">
            <h3 margin="0" padding="0">{{dente.numero}}</h3>
            <Esquema width="200" height="100" margin="0" padding="0" />
            </div>
        </div>
        </div>
        <div class="q3"> 
          <div  v-bind:key="dente.id" v-for="dente in dentes3">
                        <div class = "dentind">
            <Esquema width="200" height="100"  margin="0" padding="0"/>
            <h3 margin="0" padding="0">{{dente.numero}}</h3>
            <img  v-bind:src='"./assets/Prancheta 2Dente "+dente.numero+".svg"' width="200" height="100" margin="0" padding="0">
            
            </div>
        </div>
        </div>
        <div class="q4">
          <div v-bind:key="dente.id" v-for="dente in dentes4">
            
                       <div class = "dentind">
               <Esquema width="200" height="100" margin="0" padding="0"/>
            <h3 margin="0" padding="0">{{dente.numero}}</h3>
            <img  v-bind:src='"./assets/Prancheta 2Dente "+dente.numero+".svg"' width="200" height="100" margin="0" padding="0">
            </div>
          </div>
        </div>
        </div>
        <hr class="new2">
        <div class="form">
        <table>
    <tr>
        <th>Data Dentista Região Procedimento</th>
        <div class="seta-4"></div>
    </tr>
</table>
        </div>
  </div>

</template>

<script>
import OdontogramaCompleto from './components/OdontogramaCompleto'; 
import Esquema from './components/Esquema'; 

export default {
  name: 'App',
  components: {
    OdontogramaCompleto,
    Esquema
  },
  data(){
    return{
      dentes1: [
        {
          id: 1,
          numero: "11"
        },
       {
          id: 2,
          numero: "12"
        },
        {
          id: 3,
          numero: "13"
        },
        {
          id: 4,
          numero: "14"
        },
        {
          id: 5,
          numero: "15"
        },
        {
          id: 6,
          numero: "16"
        },
        {
          id: 7,
          numero: "17"
        },
        {
          id: 8,
          numero: "18"
        }],
        dentes2: [
        {
          id: 9,
          numero: "21"
        },
        {
          id: 10,
          numero: "22"
        },
        {
          id: 11,
          numero: "23"
        },
        {
          id: 12,
          numero: "24"
        },
        {
          id: 13,
          numero: "25"
        },
        {
          id: 14,
          numero: "26"
        },
        {
          id: 15,
          numero: "27"
        },
        {
          id: 16,
          numero: "28"
        }
      ],
      dentes3: [
        {
          id: 17,
          numero: "31"
        },
        {
          id: 18,
          numero: "32"
        },
        {
          id: 19,
          numero: "33"
        },
        {
          id: 20,
          numero: "34"
        },
        {
          id: 21,
          numero: "35"
        },
        {
          id: 22,
          numero: "36"
        },
        {
          id: 23,
          numero: "37"
        },
        {
          id: 24,
          numero: "38"
        }],
        dentes4:[
        {
          id: 25,
          numero: "41"
        },
        {
          id: 26,
          numero: "42"
        },
        {
          id: 27,
          numero: "43"
        },
        {
          id: 28,
          numero: "44"
        },
        {
          id: 29,
          numero: "45"
        },
        {
          id: 30,
          numero: "46"
        },
        {
          id: 31,
          numero: "47"
        },
        {
          id: 32,
          numero: "48"
        }
        ]
    }
  }
}
</script>

<style> 
@import url('https://fonts.googleapis.com/css?family=Titillium+Web&display=swap');

.dentind{
  display: flex;
  flex-direction: column;
  align-items:center;
  margin-left: -60px;
  margin-right: -60px;
}

.add {
  width: 500px;
  height: 100px;
  left: 65px;
  top: 90px;
  margin-top: 1cm;
  margin-bottom: 0.2em;
  margin-left: 0.5em;

  font-family: Titillium Web;
  font-style: normal;
  font-weight: bold;
  font-size: 30px;
  line-height: 46px;
  letter-spacing: 0.05em;
  color: #679C9A;
}

.title {
  width: 134px;
  height: 28px;
  left: 893px;
  top: 14px;
  margin-left: 19.2em;
  margin-top: 0.1cm;
  margin-bottom: 2mm;

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

hr.new1 {
  height: 10px;
  border: 0;
  box-shadow: 0 10px 10px -10px #8c8c8c inset;
  
}

hr.new2{
  height: 10px;
  border: 0;
  box-shadow: 0 10px 10px -10px #8c8c8c inset;
}

.button{
  float: left; 
  border:1px solid; 
  padding: 8px 45px; 
  vertical-align: middle; 
  background:#00476B; 
  color:white;
  border-radius:6px; 
  font-size: 20px; 
  font-family:helvetica, serif;
  text-decoration:none;
  margin-left: 7em;
  margin-bottom: 5mm;
}

.pointer{
  float: left; 
  border:1px solid; 
  padding: 7px 15px; 
  vertical-align: middle; 
  background:#00476B; 
  color:white;
  border-radius:6px; 
  font-size: 20px; 
  font-family:helvetica, serif;
  text-decoration:none;
  margin-left: 2em;
  margin-bottom: 5mm;
}

.pointers{
  float: left; 
  border:1px solid; 
  padding: 7px 15px; 
  vertical-align: middle; 
  background:#00476B; 
  color:white;
  border-radius:6px; 
  font-size: 20px; 
  font-family:helvetica, serif;
  text-decoration:none;
  margin-left: 0.9em;
  margin-bottom: 5mm;
}

.pointers2{
  float: left; 
  padding: 10px 15px; 
  vertical-align: middle;
  margin-left: 1.9em;
  margin-bottom: 5mm;
  margin-top: -4.4em;
}

.icons{
  float: left; 
  border:2px solid;
  border-color: #00476B; 
  padding: 22px 128px; 
  vertical-align: middle; 
  background:whitesmoke; 
  color:white;
  border-radius:6px; 
  font-size: 20px; 
  font-family:helvetica, serif;
  text-decoration:none;
  margin-left: 2em;
  margin-bottom: 5mm;
}

.icons2{
  float: left; 
  padding: 10px 15px; 
  vertical-align: middle;
  margin-left: 3em;
  margin-bottom: 5mm;
  margin-top: -4.4em;
}

.icons3{
  float: left; 
  padding: 10px 15px; 
  vertical-align: middle;
  margin-left: 2em;
  margin-bottom: 5mm;
  margin-top: -4.4em;
}

.icons4{
  float: left; 
  padding: 10px 15px; 
  vertical-align: middle;
  margin-left: 14.5em;
  margin-bottom: 5mm;
  margin-top: -4.6em;
}

.logo{
  float: left; 
  padding: 10px 15px; 
  vertical-align: middle;
  margin-left: 14.5em;
  margin-bottom: 5mm;
  margin-top: -10.4em;
}

.form{
  width: 1349px;
  height: 50px;
  left: 65px;
  top: 982px;
  background: #679C9A;
  color:white;
  font-family: 'Titillium Web', sans-serif;
  font-size: 25px;
  word-spacing: 10em;
  margin-top: 0.3cm;
  margin-left: 0.1em;
}

.seta-4{ 
  border-bottom: 20px solid whitesmoke; 
  border-left: 10px solid transparent;  
  border-right: 10px solid transparent; 
  float:right;
  margin-top: 0.3cm;
  margin-left: 6em;
}

.q1 {
  border: lightgray;
  border-right-style: dashed;
  border-bottom-style: dashed;
   padding: 20px;
  grid-area: q1;
  display: flex;
  flex-direction: row-reverse;
}
.q2 {
    border: lightgray;
  border-left-style:dashed;
  border-bottom-style: dashed;
   padding: 20px;
  grid-area: q2;
  display: flex;
  flex-direction: row;
}
.q3 {
  border: lightgray;
  border-right-style: dashed;
  border-top-style: dashed;
   padding: 20px;
  grid-area: q3;
  display: flex;
  flex-direction: row-reverse;
}
.q3 > *{
  float: left;
}
.q4 {
    border: lightgray;
  border-left-style: dashed;
  border-top-style: dashed;
   padding: 20px;
  grid-area: q4;
  display: flex;
  flex-direction: row;
}


.odontograma{
 
  display: grid;
  grid-template-columns:  1fr 1fr;
  grid-template-rows: 1fr 1fr;
  grid-template-areas: 
    "q1 q2"
    "q3 q4";
}

*{
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}
body{
  font-family: Arial, Helvetica, sans-serif;
  line-height: 1.4;
  background-color: #F1F2F3;
}
</style>