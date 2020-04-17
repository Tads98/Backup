<template>
  <div id="app">
    <div id="img5">
      <img alt="icon" src="./assets/icon.png" width="30" height="30">
    </div>
    <div id="img20">
      <img alt="Ellipse 11" src="./assets/Ellipse 11.png" width="30" height="30">
    </div>
    <div id="img21">
      <img alt="eli12" src="./assets/eli12.png" width="20" height="20">
    </div>
    <progresso msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import progresso from './components/progresso.vue'

export default {
  name: 'App',
  components: {
    progresso
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
  margin-top: -5px;
}

#img5{
  position: absolute; 
	right: 90px; 
	top: 3px;
  margin-right: -15mm;
  max-width: 200px;
  max-height: 200px;
  float: left;  
  padding: -1px 5px; 
}

#img20{
  position: absolute; 
	right: 1275px; 
	top: -5px;
  margin-left: 10mm;
  margin-top: 1mm; 
  max-width: 200px;
  max-height: 200px;
  float: left;  
  padding: 5px 10px; 
  vertical-align: middle;   
}

#img21{
  position: absolute; 
	right: 1280px; 
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
