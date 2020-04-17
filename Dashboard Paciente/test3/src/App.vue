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
            <dashboard dashboard/>
            <bloco1 Bloco1/>
            <bloco2 Bloco2/>
            <bloco3 Bloco3/>
            <bloco4 Bloco4/>
        </div>
</template>

<script>
    import dashboard from './components/dashboard.vue'
    import Bloco1 from './components/Bloco1.vue'
    import Bloco2 from './components/Bloco2.vue'
    import Bloco3 from './components/Bloco3.vue'
    import Bloco4 from './components/Bloco4.vue'

export default {
name: 'App',
components: {
    dashboard,
    Bloco1,
    Bloco2,
    Bloco3,
    Bloco4
},

    props: ["dashboard", "Bloco1", "Bloco2", "Bloco3", "Bloco4"]
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

.retangulo {
position: absolute;
width: 600px;
height: 330px;
left: 65px;
top: 90px;

background: #FFFFFF;
box-shadow: 0px 4px 25px rgba(0, 0, 0, 0.15);
border-radius: 15px;
}

body{
font-family: Arial, Helvetica, sans-serif;
line-height: 1.4;
background-color: #F1F2F3;
}
</style>
