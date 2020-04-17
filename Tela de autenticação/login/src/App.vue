<template>
  <div id="app">
    <div id="img5">
      <img alt="icon" src="./assets/Petrus.png" width="100" height="100">
    </div>
    <div id="img6">
      <img alt="logo-sabia" src="./assets/logo-sabia.png" width="25" height="25">
    </div>
    <login msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import login from './components/login.vue'

export default {
  name: 'App',
  components: {
    login
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

#img5{
  position: absolute; 
	right: 30px; 
	top: 150px;
  margin-right: 150mm;
  max-width: 200px;
  max-height: 200px;
  float: left;  
  padding: -1px 5px; 
}

#img6{
  position: absolute; 
	right: 30px; 
	top: 500px;
  margin-right: 198mm;
  max-width: 200px;
  max-height: 200px;
  float: left;  
  padding: -1px 5px; 
}

body{
  font-family: Arial, Helvetica, sans-serif;
  line-height: 1.4;
  background-color: #F1F2F3;
}
</style>
