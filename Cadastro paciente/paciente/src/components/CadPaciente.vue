<template>
  <div id="tudo">
    <div id="top">
      <img src=""/>
      <p>CADASTRAR NOVO PACIENTE </p>
      <a href="#">x</a>
    </div>
    <div id="bottom">
    
    <div id="b">
      <input size="75" type="text" class="inputText" placeholder="Nome Completo"/>
    </div>

    <div id="b">
      <input size="75" type="text" class="inputText" placeholder="Email" />
    </div>

    <div id="celular">  
      <input size="35" type="text" class="inputText" placeholder="Celular" />
    </div>

    <div id="telefone">
      <input size="35" type="text" class="inputText" placeholder="Telefone" />
    </div>

    <div id="nasc">  
      <input size="35" type="text" class="inputText" placeholder="Data de Nascimento" />
    </div>

    <div id="sexo">  
      <input size="35" type="text" class="inputText" placeholder="Sexo" />
    </div>

    <div id="prof">  
      <input size="35" type="text" class="inputText" placeholder="Profissão" />
    </div>

    <div id="cpf">  
      <input size="35" type="text" class="inputText" placeholder="CPF" />
    </div>

    <div id="rg">  
      <input size="35" type="text" class="inputText" placeholder="RG" />
    </div>

    <div id="exp">  
      <input size="35" type="text" class="inputText" placeholder="Orgão Expedidor" />
    </div>

    <div id="pass">  
      <input size="75" type="text" class="inputText" placeholder="Número de Passaporte" />
    </div>

    <div id="row13" class="row">
      <select class="test">
                    <option value="">Estado Cívil</option>    
                    <option value="Solteiro(a)">Solteiro(a)</option>
                    <option value="Casado(a)">Casado(a)</option>
      </select>
    </div>
    <div id="row14" class="row">
    <button type="submit">PRÓXIMO</button>
    </div>
  </div>
  </div>
</template>

<script>
export default {
  name: 'CadPaciente',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
@import url("https://fonts.googleapis.com/css?family=Titillium+Web&display=swap");

  *{
    font-family: 'Titillium Web', sans-serif;
}
a{
 text-decoration: none;   
 color: #fff;
 margin-left: auto;
  order: 2;
}

#b{
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: center;
    margin: 10px;
    margin-top: -3px;
    margin-left: 0.8cm;
    margin-bottom: 10px;
    width: 11cm;
    height: 0.8cm;
    
}

#celular{
    margin-top: -3px;
    margin-left: 0.1cm;
    margin-bottom: 10px;
    width: 5cm;
}

#telefone{
    margin-top: -36px;
    margin-left: 6.4cm;
    margin-bottom: 20px;
    width: 5cm;  
}

#nasc{
    margin-top: -11px;
    margin-left: 1mm;
    margin-bottom: 20px;
    width: 5cm;  
}

#sexo{
    margin-top: -46px;
    margin-left: 6.4cm;
    margin-bottom: 20px;
    width: 5cm;  
}

#prof{
    margin-top: -10px;
    margin-left: 0.1cm;
    margin-bottom: 20px;
    width: 5cm;  
}

#cpf{
    margin-top: -46px;
    margin-left: 6.4cm;
    margin-bottom: 20px;
    width: 5cm;  
}

#rg{
    margin-top: -10px;
    margin-left: 0.1cm;
    margin-bottom: 20px;
    width: 5cm;  
}

#exp{
    margin-top: -46px;
    margin-left: 6.4cm;
    margin-bottom: 20px;
    width: 5cm;  
}

#pass{
    margin-top: -10px;
    margin-left: 0.1cm;
    margin-bottom: 20px;
    width: 5cm;  
}

.test{
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: center;
    margin: 10px;
    margin-top: -10px;
    margin-left: 0.1cm;
    margin-bottom: 15px;
    width: 12.4cm;
    height: 0.8cm;
    
}

#tudo{
    background-color:#F1F2F3;
    width: 500px;
    height: 475px;
    display: grid;
    border-radius: 10px;
    margin-left: 10cm;
}
#top{
    font-size: 14px;
    font-weight: bold;
    padding-bottom:2px;
    padding-top: 2px;
    align-items: center;
    display: flex;
    padding-left: 8%;
     padding-right: 8%;
    border-top-left-radius: 10px;
    border-top-right-radius: 10px;
    color: #F1F2F3;
    background-color: #00476B;
}

button {
  background-color: #00476B;
  color: white;
  padding: 5px 10px;
  margin: 5px 0;
  border-radius: 5px;
  cursor: pointer;
  position: absolute;
  width: 200px;
  height: 40px;
  left: 670px;
  top: 470px;
  bottom: 100px;
}

button:hover {
  opacity: 0.8;
}

#bottom{
    padding: 10px;
}
input{
 padding-left: 5px;    
}
</style>
