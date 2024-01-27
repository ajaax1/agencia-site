<template>
    <section v-motion-slide-visible-left class="third-section d-flex justify-content-center align-items-center">
        <div class="div-third-section gap-2">
            <h1>Por que nós?</h1>
            <p>Uma experiência incrível para seus clientes, resultados espetaculares para sua empresa.</p>
            <div class="cards-div d-flex justify-content-around align-items-center gap-2">
                <div class="card">
                    <img src="../assets/img/ICONE1.png" alt="">
                    <h2>Planejamento impecável</h2>
                    <p>Conte com a Agência Bold como sua parceira no planejamento de seus projetos, conteúdos, campanhas,
                        estratégias. Nossos profissionais altamente qualificados estão preparados para qualquer desafio.</p>
                </div>
                <div class="card">
                    <img src="../assets/img/ICONE2.png" alt="">
                    <h2>Pague pelos resultados</h2>
                    <p>Aqui você paga de acordo com o retorno que ganha em cada campanha. Não deixe a oportunidade de ter
                        melhores resultados para amanhã. Entre em contato e vamos conversar sobre sua necessidade.</p>
                </div>
                <div class="card">
                    <img src="../assets/img/ICONE3.png" alt="">
                    <h2>Suporte e acompanhamento</h2>
                    <p>Mesmo após terminarmos nosso projeto ou estratégia, nós da Agência Bold acompanharemos os futuros
                        desdobramentos e resultados oferecendo todo suporte possível para você e sua equipe.
                    </p>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {

}
</script>

<style>
.third-section {
    width: 100%;
    font-family: 'Raleway', sans-serif;
    text-align: center;
    margin-bottom: 5rem;
}

.div-third-section {
    width: 1250px;

}

.third-section p {
    color: #7E92AC;
    font-weight: 100;
    margin-bottom: 5rem;
}

.third-section h1 {
    color: #000000;
    font-weight: 800;
    font-family: 'Raleway', sans-serif;

}

.cards-div {
    width: 100%;
    text-align: start;
    font-size: 15px;
    border-radius: 10px;
    flex-wrap: wrap;
    padding: 0.5rem;
}

.card:hover {
    transform: scale(1.05);
}

.cards-div p {
    font-size: 15px;
    margin-bottom: 0 !important;
}

.cards-div h2 {
    font-size: 25px;
    color: #000000;
    font-weight: 800;
    font-family: 'Raleway', sans-serif;
}

.card {
    background-color: white;
    padding: 1rem;
    max-width: 24rem;
    max-height: 18rem;
    transition: transform 0.3s ease;
}

.card img {
    width: 100px;
    height: 100px;
}

@media only screen and (max-width: 808px) {
    .cards-div {
        justify-content: center !important;
        width: 100%;
    }

    .div-third-section {
        width: 100%;
    }
}

@media only screen and (max-width: 500px) {
    .cards-div {
        justify-content: center !important;
        width: 100%;
    }

    .div-third-section {
        width: 100%;
    }

    .card {
        max-width: 25rem;
        height: 100%;
        transition: transform 0.3s ease;
        text-align: center;
        padding: 1rem;
        display: flex;
        align-items: center;
    }

    .card img {
        display: none;
    }

}</style>