<template>
<div>
     <div class="keys">
  <div class="up arr"><i class="fa fa-arrow-up">
      
      
      </i></div>
  <br />
  </div>
</div>


</template>

<script>
export default {
    name: "Esquema",
    props: ["esquemas"]
}
</script>
<style lang="stylus" scoped>
@import url(https://fonts.googleapis.com/css?family=Lato:300);

/*Bola maior*/
.keys {
  font-family: 'Lato', sans-serif;    
  text-align: center;
  width: 50px;
  height: 70px;
}

/*Bola menor*/
.arr {
    border-radius: 500px;
  cursor: pointer;
  width: 50px;
  height: 50px;
  text-align: center;
  line-height: 100px;
  background: #00476B;
  color: white;
  font-size: 50px;
  border-right: 10px solid darken(blue, 20);
  border-bottom: 10px solid lightness(blue, 20);
  border-left: 10px solid lighten(teal, 15);
  border-top: 10px solid darken(aquamarine, 10);  
  display: inline-block;
  margin: 5px;

  &:active {
    border-bottom: 8px solid darken(grey, 20);
    text-shadow: 0 0 10px white, 0 0 10px white, 0 0 20px white;    
    transform: translate(0, 2px);
  }
  user-select: none;
}



</style>