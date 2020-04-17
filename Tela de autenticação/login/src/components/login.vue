<template>
<div>
  
<form action="/action_page.php" method="post">
  <div class="container">
    <h2>Entrar</h2>
    <input type="text" placeholder="Nome" name="uname" required>

    <input type="password" placeholder="Senha" name="psw" required>
        
    <button type="submit">Login</button>
  </div>
</form>
</div>
</template>

<script>
export default {
  name: 'login',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  body {font-family: Arial, Helvetica, sans-serif;}
form {border: 3px solid #f1f1f1;}

input[type=text], input[type=password] {
  width: 100%;
  padding: 12px 20px;
  margin: 8px 0;
  display: inline-block;
  border: 1px solid #ccc;
  box-sizing: border-box;
}

button {
  background-color: #679C9A;
  color: white;
  padding: 14px 20px;
  margin: 8px 0;
  border-radius: 5px;
  cursor: pointer;
  position: absolute;
  width: 470px;
  height: 53px;
  left: 457px;
  top: 415px;
}

button:hover {
  opacity: 0.8;
}

.cancelbtn {
  width: auto;
  padding: 10px 18px;
  background-color: #f44336;
}

.imgcontainer {
  text-align: center;
  margin: 24px 0 12px 0;
}

img.avatar {
  width: 40%;
  border-radius: 50%;
}

.container {
  padding: 16px;
  width: 470px;
  margin-top: 4cm;
  margin-left: 11.4cm;
}

.container2 {
  padding: 16px;
  width: 470px;
  margin-top: 1cm;
  margin-left: 8cm;
  color: #EC8C67;
}

span.psw {
  float: right;
  padding-top: 16px;
}

/* Change styles for span and cancel button on extra small screens */
@media screen and (max-width: 300px) {
  span.psw {
     display: block;
     float: none;
  }
  .cancelbtn {
     width: 100%;
  }
}

</style>
