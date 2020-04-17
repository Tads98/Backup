<template>
    <div>
        <div id="tudo">
        <div id="top">
        <img src=""/>
        <p>CADASTRAR NOVO PACIENTE</p>
        <a href="#">x</a>
        </div>
        <div id="bottom">
        <div id="b">
        <input size="75" type="text" class="inputText" placeholder="Endereço Profissional"/>
    </div>

<div id="b">
    <input size="75" type="text" class="inputText" placeholder="Endereço Residêncial" />
</div>

<div id="row13" class="row">
    <select class="test">
        <option value="">Convênio</option>    
        <option value="Solteiro(a)">Solteiro(a)</option>
        <option value="Casado(a)">Casado(a)</option>
    </select>
</div>

<div id="b">
    <input size="75" type="text" class="inputText" placeholder="Número de CNS" />
</div>

<div>
    <select id="pass">
    <option value="">Naturalidade</option>    
    <option value="Solteiro(a)">Solteiro(a)</option>
    <option value="Casado(a)">Casado(a)</option>
    </select>
</div>
<div>
    <select id="pass2">
    <option value="">Nacionalidade</option>    
    <option value="Solteiro(a)">Solteiro(a)</option>
    <option value="Casado(a)">Casado(a)</option>
    </select>
</div>
<div>
    <button type="submit">ANTERIOR</button>
</div>
<div>
    <button class="t" type="submit">SALVAR</button>
</div>
</div>
</div>
</div>
</template>

<script>
export default {
    name: 'final',
    props: ["final"]
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
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


.test{
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: center;
    margin: 10px;
    margin-top: -3px;
    margin-left: 0.2cm;
    margin-bottom: 15px;
    width: 12.3cm;
    height: 0.8cm;
}

#pass{
    margin-top: -10px;
    margin-left: -7.5cm;
    margin-bottom: 20px;
    width: 5cm;
}

#pass2{
    margin-top: -20cm;
    margin-left: -7.5cm;
    margin-bottom: 20px;
    width: 5cm;  
}

#tudo{
    background-color:lightgray;
    width: 500px;
    display: grid;
    border-radius: 10px;
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
    color: #fff;
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
    width: 80px;
    height: 40px;
    left: 250px;
    top: 300px;
    bottom: 100px;
}

.t{
    background-color: #00476B;
    color: white;
    padding: 5px 10px;
    margin: 5px 0;
    border-radius: 5px;
    cursor: pointer;
    position: absolute;
    width: 80px;
    height: 40px;
    left: 350px;
    top: 300px;
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
@import url("https://fonts.googleapis.com/css?family=Titillium+Web&display=swap");
</style>
