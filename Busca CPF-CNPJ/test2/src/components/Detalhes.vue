<template>
  <div id="tudo">
    <div id="top">
      <img src=""/>
      <p>UBS Jiqui </p>
      <a href="#">x</a>
    </div>
    <div id="bottom">
    <div id="row2" class="row">
      <img src="..\assets\Vector (2).png" />
      <input type="text" class="inputText" placeholder="CNPJ"/>
    </div>
    <div id="row3" class="row">
      <img src="..\assets\Vector (3).png" />
      <input type="text" class="inputText" placeholder="Endereço" />
    </div>
     <div id="row4" class="row">
      <img src="..\assets\Vector (4).png" />
      <input type="text" class="inputText" placeholder="Telefone" />
    </div>
    </div>
  </div>
</template>

<script>

export default {
  name: "Busca",
  props: {
    msg: String
  }
};
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


.row{
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: center;
    margin: 10px;
    margin-top: 15px;
    margin-bottom: 15px;
}
.row > img{
    margin-right: 10px;
    height: 12px;
    width: 12px;
}
.row > input{
    width: 90%;
    height: 30px;
    background-color: rgba(0, 71, 107, 0.08);
    border-bottom-style: solid;
    border-bottom: #00476B;
    border-top: none;
    border-left: none;
    border-right: none;
}
#tudo{
    background-color:#fff;
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

#bottom{
    padding: 10px;
}

input{
 padding-left: 5px;    
}


@import url("https://fonts.googleapis.com/css?family=Titillium+Web&display=swap");
</style>
