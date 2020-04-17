<template>
    <div>
        <div class="title">
            <p>Petrus</p>
            </div>
            <hr class="new2">
    </div>
</template>

<script>
export default {
    name: 'dashboard',
    props: ["dashboard"]
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

hr.new2{
    height: 10px;
    border: 0;
    box-shadow: 0 10px 10px -10px #8c8c8c inset;
}


.retangulo7 {
    position: absolute;
    width: 485px;
    height: 50px;
    left: 50px;
    top: 190px;
    cursor: pointer;

    background: #F4F4F4;
    box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.25);
    border-radius: 15px;
}

</style>
