<template>
  <div>
    <div class="title">
      <p>Petrus</p>
    </div>
    <hr class="bar">
  </div>

</template>

<script>
export default {
  name: 'progresso',
  props: ["Progresso"]    
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

hr.bar{
  height: 10px;
  border: 0;
  box-shadow: 0 10px 10px -10px #8c8c8c inset;
}

.text4{
  position: absolute;
  width: 375.9px;
  height: 27px;
  left: 755px;
  top: 75px;
  margin-left: 10cm;

  font-family: Titillium Web;
  font-style: normal;
  font-weight: normal;
  font-size: 18px;
  line-height: 27px;
  display: flex;
  align-items: center;

  color: #353535;
}
</style>
