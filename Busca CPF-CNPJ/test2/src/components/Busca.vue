<template>
  <div>
  <div class="title">
      <p>Petrus</p>
      </div>
      <hr class="new2">
      <div>
      <table>
        <tr>
        <td>
          <div class="add">
          <p>ESTABELECIMENTOS E PROFISSIONAIS</p>
          </div>
        </td>
        </tr>
    </table>
    <table>
      <tr>
        <td>
          <div class="add">
          <p>NOME</p>
          </div>
        </td>
        <td>
          <div class="doc">
          <p>CPF/CNPJ</p>
          </div>
        </td>
      </tr>
    </table>
      </div>
      <hr class="new1">
      <div class="form">
        <table>
      <tr>
        <td>
          <div class="add1">
          <p>UBS Jiqui</p>
          </div>
        </td>
        <td>
          <div class="doc1">
          <p>00.000.000/0000-00</p>
          </div>
        </td>
      </tr>
    </table>
        </div>
        <div class="form1">
        <table>
      <tr>
        <td>
          <div class="add1">
          <p>UBS Nova Parnamirim</p>
          </div>
        </td>
        <td>
          <div class="doc1">
          <p>00.000.000/0000-00</p>
          </div>
        </td>
      </tr>
    </table>
    <div class="form2">
        <table>
      <tr>
        <td>
          <div class="add1">
          <p>UBS Parque das Orquídeas</p>
          </div>
        </td>
        <td>
          <div class="doc1">
          <p>00.000.000/0000-00</p>
          </div>
        </td>
      </tr>
    </table>
        </div>
</div>
    <div class="form3">
        <table>
      <tr>
        <td>
          <div class="add1">
          <p>UBS Reginaldo Fernandes</p>
          </div>
        </td>
        <td>
          <div class="doc1">
          <p>00.000.000/0000-00</p>
          </div>
        </td>
      </tr>
    </table>
        </div>
    <div class="form4">
        <table>
      <tr>
        <td>
          <div class="add1">
          <p>UBS Rocas I</p>
          </div>
        </td>
        <td>
          <div class="doc1">
          <p>00.000.000/0000-00</p>
          </div>
        </td>
      </tr>
    </table>
    </div>
    <div class="form5">
        <table>
      <tr>
        <td>
          <div class="add1">
          <p>Dr. João Pereira Gomes</p>
          </div>
        </td>
        <td>
          <div class="doc1">
          <p>000.000.000-00</p>
          </div>
        </td>
      </tr>
    </table>
    </div>
    <div class="form6">
        <table>
      <tr>
        <td>
          <div class="add1">
          <p>Dra. Maria das Vitórias Mendonça</p>
          </div>
        </td>
        <td>
          <div class="doc1">
          <p>000.000.000-00</p>
          </div>
        </td>
      </tr>
    </table>
    </div>
</div>
</template>

<script>
export default {
  name: 'Busca',
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

hr.new1 {
  border: 1px solid #679C9A;
  border-radius: 5px; 
  margin-bottom: 10cm;
  margin-top: -3em;
}

hr.new2{
  height: 10px;
  border: 0;
  box-shadow: 0 10px 10px -10px #8c8c8c inset;
}

.add {
  width: 500px;
  height: 100px;
  left: 65px;
  top: 90px;
  margin-top: 1cm;
  
  margin-left: 0.5em;

  font-family: Titillium Web;
  font-style: normal;
  font-weight: bold;
  font-size: 25px;
  line-height: 46px;
  letter-spacing: 0.05em;
  color: #679C9A;
}

.add1 {
  width: 500px;
  height: 100px;
  left: 65px;
  top: 90px;
  margin-top: -0.7cm;
  
  margin-left: 0.5em;

  font-family: Titillium Web;
  font-style: normal;
  font-weight: bold;
  font-size: 25px;
  line-height: 46px;
  letter-spacing: 0.05em;
  color: whitesmoke;
}

.doc {
  width: 500px;
  height: 100px;
  left: 65px;
  top: 90px;
  margin-top: 1cm;
  margin-left: 5cm;

  font-family: Titillium Web;
  font-style: normal;
  font-weight: bold;
  font-size: 25px;
  line-height: 46px;
  letter-spacing: 0.05em;
  color: #679C9A;
}

.doc1 {
  width: 500px;
  height: 100px;
  left: 65px;
  top: 90px;
  margin-top: -0.7cm;
  margin-left: 5cm;

  font-family: Titillium Web;
  font-style: normal;
  font-weight: bold;
  font-size: 25px;
  line-height: 46px;
  letter-spacing: 0.05em;
  color: whitesmoke;
}

.nome {
  width: 500px;
  height: 100px;
  left: 65px;
  top: 90px;
  margin-top: 1cm;
  margin-bottom: 0.2em;
  margin-left: 1cm;

  font-family: Titillium Web;
  font-style: normal;
  font-weight: bold;
  font-size: 25px;
  line-height: 46px;
  letter-spacing: 0.05em;
  color: #679C9A;
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
  padding: 22px 25px; 
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
  padding: 22px 25px; 
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

.form{
  width: 1331px;
  height: 50px;
  left: 65px;
  top: 982px;
  background: #679C9A;
  color:white;
  font-family: 'Titillium Web', sans-serif;
  font-size: 25px;
  margin-left:  0em;
  margin-top: -14em;
  border-radius:6px;
}

.form1{
  width: 1331px;
  height: 50px;
  left: 65px;
  top: 982px;
  background: #679C9A;
  color:white;
  font-family: 'Titillium Web', sans-serif;
  font-size: 25px;
  margin-left:  0em;
  margin-top: 1em;
  border-radius:6px;
}

.form2{
  width: 1331px;
  height: 50px;
  left: 65px;
  top: 982px;
  background: #679C9A;
  color:white;
  font-family: 'Titillium Web', sans-serif;
  font-size: 25px;
  margin-left:  0em;
  margin-top: -1em;
  border-radius:6px;
}

.form3{
  width: 1331px;
  height: 50px;
  left: 65px;
  top: 982px;
  background: #679C9A;
  color:white;
  font-family: 'Titillium Web', sans-serif;
  font-size: 25px;
  margin-left:  0em;
  margin-top: 4.3em;
  border-radius:6px;
}

.form4{
  width: 1331px;
  height: 50px;
  left: 65px;
  top: 982px;
  background: #679C9A;
  color:white;
  font-family: 'Titillium Web', sans-serif;
  font-size: 25px;
  margin-left:  0em;
  margin-top: 1.5em;
  border-radius:6px;
}

.form5{
  width: 1331px;
  height: 50px;
  left: 65px;
  top: 982px;
  background: #679C9A;
  color:white;
  font-family: 'Titillium Web', sans-serif;
  font-size: 25px;
  margin-left:  0em;
  margin-top: 1.5em;
  border-radius:6px;
}

.form6{
  width: 1331px;
  height: 50px;
  left: 65px;
  top: 982px;
  background: #679C9A;
  color:white;
  font-family: 'Titillium Web', sans-serif;
  font-size: 25px;
  margin-left:  0em;
  margin-top: 1.5em;
  border-radius:6px;
}
</style>
