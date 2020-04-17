<template>
    <div class="retangulo3">
    <table>
        <tr>
        <td>
        <div class="retangulo9">
        </div>
        </td>
        </tr>
    </table>
        <p class="p1">PRESSÃO</p>
        <p class="p2">ALTURA</p>
        <p class="p3">MASSA C.</p>
        <p class="p4">14/9 mmHg</p>
        <p class="p5">1,70 m</p>
        <p class="p6">60 Kg</p>
        <p class="p7">Ana Maria Gomes</p>
        <p class="p8">30 Anos</p>
    </div>
</template>

<script>
export default {
    name: 'Bloco3',
    props: ["Bloco3"]
}
</script>

<style scoped>

.retangulo3 {
    position: absolute;
    width: 620px;
    height: 210px;
    left: 1027px;
    top: 53px;
    margin-left: -90mm;


    background: #FFFFFF;
    box-shadow: 1px 4px 25px rgba(0, 0, 0, 0.15);
    border-radius: 15px;
}

.retangulo9 {
    position: absolute;
    width: 510px;
    height: 100px;
    left: 50px;
    top: 80px;

    border: 1px solid #909090;
    box-sizing: border-box;
    border-radius: 15px;
}

.p1{
    position: absolute;
    width: 132px;
    height: 46px;
    left: 80px;
    top: 70px;

    font-family: Titillium Web;
    font-style: normal;
    font-weight: normal;
    font-size: 20px;
    line-height: 30px;
    

    display: flex;
    align-items: center;
    text-align: center;
    letter-spacing: 0.05em;

    color: #00476B;
}

.p2 {
    position: absolute;
    width: 132px;
    height: 46px;
    left: 270px;
    top: 70px;

    font-family: Titillium Web;
    font-style: normal;
    font-weight: normal;
    font-size: 20px;
    line-height: 30px;
    

    display: flex;
    align-items: center;
    text-align: center;
    letter-spacing: 0.05em;

    color: #00476B;
}

.p3{
    position: absolute;
    width: 132px;
    height: 46px;
    left: 400px;
    top: 70px;

    font-family: Titillium Web;
    font-style: normal;
    font-weight: normal;
    font-size: 20px;
    line-height: 30px;
    

    display: flex;
    align-items: center;
    text-align: center;
    letter-spacing: 0.05em;

    color: #00476B;
}

.p4 {
    position: absolute;
    width: 132px;
    height: 46px;
    left: 85px;
    top: 110px;

    font-family: Titillium Web;
    font-style: normal;
    font-weight: normal;
    font-size: 15px;
    line-height: 46px;
    

    display: flex;
    align-items: center;
    text-align: center;

    color: #656565;
}

.p5 {
    position: absolute;
    width: 132px;
    height: 46px;
    left: 280px;
    top: 110px;

    font-family: Titillium Web;
    font-style: normal;
    font-weight: normal;
    font-size: 15px;
    line-height: 46px;
    

    display: flex;
    align-items: center;
    text-align: center;

    color: #656565;
}

.p6 {
    position: absolute;
    width: 132px;
    height: 46px;
    left: 425px;
    top: 110px;

    font-family: Titillium Web;
    font-style: normal;
    font-weight: normal;
    font-size: 15px;
    line-height: 46px;


    display: flex;
    align-items: center;
    text-align: center;

    color: #656565;
}

.p7{
    position: absolute;
    width: 132px;
    height: 46px;
    left: 250px;
    top: -5px;

    font-family: Titillium Web;
    font-style: normal;
    font-weight: 600;
    font-size: 14px;
    line-height: 25px;
    

    display: flex;
    align-items: center;
    text-align: center;
    text-decoration-line: underline;
}

.p8{
    position: absolute;
    width: 132px;
    height: 46px;
    left: 285px;
    top: 15px;

    font-family: Titillium Web;
    font-style: normal;
    font-weight: 600;
    font-size: 14px;
    line-height: 25px;


    display: flex;
    align-items: center;
    text-align: center;
    color: #353535;
}

</style>