<template>
    <div class="retangulo2">
        <h1 class="titulo">Resumo do Tratamento Atual</h1>
            <p class="lorem">
            Lorem Ipsum is simply 
            dummy text of the printing and typesetting industry. 
            Lorem Ipsum has been the industry's standard dummy 
            text ever since the 1500s, when an unknown printer 
            took a galley of type and scrambled it to make a 
            type specimen book. It has survived not only five centuries,
            but also the leap into electronic typesetting, remaining 
            essentially unchanged. It was popularised in the 1960s 
            with the release of Letraset sheets containing Lorem Ipsum passages.
            </p>
            <p>
            <a href="" class="p">IR PARA O TRATAMENTO</a>
            </p>
    </div>
</template>

<script>
export default {
    name: 'Bloco2',
    props: ["Bloco2"]    
}
</script>

<style scoped>

.retangulo2 {
    position: absolute;
    width: 600px;
    height: 200px;
    left: 65px;
    top: 500px;
    margin-top: -25mm;
    margin-bottom: 5mm;

    background: #FFFFFF;
    box-shadow: 1px 8px 25px rgba(0, 0, 0, 0.15);
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

    display: flex;
    align-items: center;
    letter-spacing: 0.05em;

    color: #679C9A;
}

.lorem {
    position: absolute;
    width: 510px;
    height: 50px;
    left: 30px;
    top: 60px;

    font-family: Titillium Web;
    font-style: normal;
    font-weight: 300;
    font-size: 13px;
    line-height: 13px;
    display: flex;
    align-items: center;
    letter-spacing: 0.05em;

    color: #656565;
}

.p {
    position: absolute;
    width: 233px;
    height: 30px;
    left: 30px;
    top: 130px;

    font-family: Titillium Web;
    font-style: normal;
    font-weight: 600;
    font-size: 15px;
    line-height: 30px;
    display: flex;
    align-items: center;
    letter-spacing: 0.05em;
    text-decoration-line: underline;
}

</style>