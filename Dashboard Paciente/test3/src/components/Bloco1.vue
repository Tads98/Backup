<template>
    <div class="retangulo">
        <h1 class="titulo">Histórico de Tratamentos</h1>
        <table>
        <tr>
        <td>
    <div class="retangulo5">
        <a href="">
        <table>
        <div class="linha"></div>
        <tr>
        <td class="ex">
        <p>Nome do Exame</p>
        </td>
        <td class="ex1">
        <p>Dr. Nome do Dentista</p>
        </td>
        <td class="ex2">
        <li>Em aberto</li>
        </td>
        </tr>
        </table>
        </a>
    </div>
    </td>
    </tr>
    <tr>
    <td>
    <div class="retangulo6">
        <a href="">
        <table>
        <tr>
        <td class="ex">
        <p>Nome do Exame</p>
        </td>
        <td class="ex1">
        <p>Dr. Nome do Dentista</p>
        </td>
        <td class="ex2">
        <li>Em aberto</li>
        </td>
        </tr>
        </table>
        </a>
    </div>
    </td>
    </tr>
    <tr>
    <td>
    <div class="retangulo7">
        <a href="">
        <table>
        <tr>
        <td class="ex">
        <p>Nome do Exame</p>
        </td>
        <td class="ex1">
        <p>Dr. Nome do Dentista</p>
        </td>
        <td class="ex3">
        <li>Finalizado</li>
        </td>
        </tr>
        </table>
        </a>
    </div>
    </td>
    </tr>
    <tr>
    <td>
    <div class="retangulo8">
        <a href="">
        <table>
        <tr>
        <td class="ex">
        <p>Nome do Exame</p>
        </td>
        <td class="ex1">
        <p>Dr. Nome do Dentista</p>
        </td>
        <td class="ex4">
        <li>Cancelado</li>
        </td>
        </tr>
        </table>
        </a>
    </div>
    </td>
    </tr>
    </table>
    </div>
</template>

<script>
export default {
name: 'Bloco1',
props: ["Bloco1"]    
}
</script>

<style scoped>

.retangulo {
    position: absolute;
    width: 600px;
    height: 330px;
    left: 65px;
    top: 90px;
    margin-top: -10mm;

    background: #FFFFFF;
    box-shadow: 0px 4px 25px rgba(0, 0, 0, 0.15);
    border-radius: 15px;
}

h1.titulo {
    position: absolute;
    width: 535px;
    height: 46px;
    left: 30px;
    top: -10px;

    font-family: Titillium Web;
    font-style: normal;
    font-weight: bold;
    font-size: 21px;
    line-height: 46px;
    /* identical to box height */

    display: flex;
    align-items: center;
    letter-spacing: 0.05em;

    color: #679C9A;
}

.retangulo5 {
    position: absolute;
    width: 485px;
    height: 50px;
    left: 50px;
    top: 50px;
    cursor: pointer;
    background: #F4F4F4;
    box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.25);
    border-radius: 15px;
}

.linha{
    height: 300px;
    border-left: 2.5px solid rgba(149, 149, 149, 0.5);
    margin-left: 510px;
    margin-top: -1cm;
}

.ex {
    position: absolute;
    width: 198px;
    height: 30px;
    left: 15px;
    top: 10px;

    font-family: Titillium Web;
    font-style: normal;
    font-weight: 600;
    font-size: 15px;
    line-height: 30px;
    display: flex;
    align-items: center;
    letter-spacing: 0.05em;

    color: #00476B;
}

.ex1 {
    position: absolute;
    width: 199px;
    height: 30px;
    left: 160px;
    top: 10px;

    font-family: Titillium Web;
    font-style: normal;
    font-weight: normal;
    font-size: 15px;
    line-height: 30px;
    display: flex;
    align-items: center;
    letter-spacing: 0.05em;

    color: #00476B;
}

.ex2 {
    position: absolute;
    width: 100px;
    height: 30px;
    left: 355px;
    top: 10px;

    font-family: Titillium Web;
    font-style: normal;
    font-weight: normal;
    font-size: 15px;
    line-height: 30px;
    display: flex;
    align-items: center;
    letter-spacing: 0.05em;
    color: #FF9929;
}

.retangulo6 {
    position: absolute;
    width: 485px;
    height: 50px;
    left: 50px;
    top: 120px;
    cursor: pointer;

    background: #F4F4F4;
    box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.25);
    border-radius: 15px;
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

.retangulo8 {
    position: absolute;
    width: 485px;
    height: 50px;
    left: 50px;
    top: 255px;
    cursor: pointer;

    background: #F4F4F4;
    box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.25);
    border-radius: 15px;
}

.ex3 {
    position: absolute;
    width: 199px;
    height: 30px;
    left: 355px;
    top: 10px;

    font-family: Titillium Web;
    font-style: normal;
    font-weight: normal;
    font-size: 15px;
    line-height: 30px;
    display: flex;
    align-items: center;
    letter-spacing: 0.05em;
    color: #03A400;
}

.ex4 {
    position: absolute;
    width: 199px;
    height: 30px;
    left: 355px;
    top: 10px;

    font-family: Titillium Web;
    font-style: normal;
    font-weight: normal;
    font-size: 15px;
    line-height: 30px;
    display: flex;
    align-items: center;
    letter-spacing: 0.05em;
    color: #BD2130;
}

</style>