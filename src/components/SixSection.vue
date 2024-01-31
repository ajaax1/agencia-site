<template>
    <section id="sixth-section" class="sixth-section d-flex justify-content-center align-items-center">
        <div class="sixth-section-div">
            <h1>Depoimentos</h1>
            <div class="div-person-cards d-flex justify-content-between align-items-center gap-4 ">
                <div class="card-person">
                    <img src="../assets/img/DEPOIMENTO1.png" alt="">
                    <h2>Miriam Souza</h2>
                    <span>Uber</span>
                    <p>O trabalho da Agência Bold foi fundamental para o nosso posicionamento e nossas estratégias de 2021.
                        Juntos tivemos excelentes resultados e nossos clientes ficaram surpresos com a qualidade. Foi um
                        trabalho incrível feito a muitas mãos pela Uber e pelo time da Agência Bold.</p>
                    <img src="../assets/img/RATE.png" alt="">
                </div>
                <div class="card-person">
                    <img src="../assets/img/DEPOIMENTO2.png" alt="">
                    <h2>Lucas Mendes</h2>
                    <span>The North Face</span>
                    <p>Buscamos a Agência Bold para nos ajudar com campanhas de growth marketing focadas em um público
                        extremamente específico. O produto teve faturamento maior que 300%.</p>
                    <img src="../assets/img/RATE.png" alt="">
                </div>
                <div class="card-person ">
                    <img src="../assets/img/DEPOIMENTO3.png" alt="">
                    <h2>Zaya Menphis</h2>
                    <span>Rappi</span>
                    <p>A estratégia de lançamento da marca não seria a mesma sem o trabalho comprometido da Agência Bold.
                        Obrigado ao Vinícius, que abraçou nossos desafios como um de nós.</p>
                    <img src="../assets/img/RATE.png" alt="">
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
.sixth-section {
    width: 100%;
    margin-bottom:10rem;
}

.sixth-section-div {
    max-width: 1250px;
    padding: 0.5rem;
}

.sixth-section-div h1 {
    color: #000000;
    font-family: 'Raleway', sans-serif;
    font-weight: 800;
    text-align: center;
    margin-bottom: 5rem;
}

.card-person {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    align-items: center;
    flex-grow: 1;
    background-color: #70707016;
    border-radius: 10px;
    text-align: center;
    min-height: 20rem;
    padding: 0.5rem;
}

.card-person img {
    transition: transform 0.3s ease;
}

.card-person img:hover {
    transform: scale(1.1);
}

@media only screen and (max-width: 1300px) {
    .div-person-cards {
        flex-wrap: wrap;
    }

    .card-person {
        justify-content: center;
    }
}
</style>