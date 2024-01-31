<template>
    <section class="fifth-section d-flex justify-content-center align-items-center">
        <div class="d-flex fifth-section-div align-items-center flex-wrap justify-content-between">
            <div class="fifth-section-left d-flex flex-column">
                <h1>Benefícios para você</h1>
                <ul>
                    <li class="image-text">
                        <img v-motion-slide-visible-bottom src="../assets/img/checklist.png" alt="">
                        <p>Garantia de resultados, pague de acordo com o desempenho do seu projeto ou campanha.</p>
                    </li>
                    <li class="image-text">
                        <img v-motion-slide-visible-bottom src="../assets/img/checklist.png" alt="">
                        <p>Equipe qualificada. Nossos profissionais possuem vasta experiência nacional e no exterior.</p>
                    </li>
                    <li class="image-text">
                        <img v-motion-slide-visible-bottom src="../assets/img/checklist.png" alt="">
                        <p>Acreditamos que trabalhos criativos são os que mais se destacam em meio a multidão. Saia do
                            feijão com arroz.</p>
                    </li>
                    <a href="#seventh-section"><button>Entrar em contato</button></a>
                </ul>
            </div>
            <img v-motion-slide-visible-bottom class="fifth-section-image" src="../assets/img/IMAGEM1.png" alt="">
        </div>
    </section>
</template>

<script>
export default {

}
</script>

<style>
.fifth-section {
    width: 100%;
    margin-bottom: 5rem;
}

.fifth-section-div {
    gap: 1rem;
    max-width: 1250px;
}

.fifth-section-div h1 {
    color: #000000;
    font-family: 'Raleway', sans-serif;
    font-weight: 800;
}

.image-text {
    display: flex;
    align-items: center;

}

.fifth-section-left {
    flex-grow: 1;
    width: 30rem;
}

.fifth-section-image {
    height: 35rem;
    width: 40rem;
}

li img {
    width: 5rem;
    height: 5rem;
}

li p {
    color: #7E92AC;
}

ul button {
    background-color: #255AFF;
    border-radius: 10px;
    height: 3rem;
    width: 11rem;
    color: white;
    text-transform: uppercase;
    border-style: none;
    font-family: 'Raleway', sans-serif;
    font-weight: 800;
    padding: 0.5rem;
    text-align: center;
    transition: transform 0.2s ease;
}

ul button:hover {
    transform: scale(1.1);
}

@media only screen and (max-width: 1234px) {
    .fifth-section-div {
        justify-content: center !important;
        align-items: center;

    }

    .fifth-section-left {
        justify-content: center !important;
        align-items: center;
        max-width: 30rem;
        text-align: center;
    }

    .fifth-section-left p {
        text-align: start;
    }

}

@media only screen and (max-width: 1134px) {
    .fifth-section-div {
        width: 80%;
        height: 80%;
    }
}

@media only screen and (max-width: 700px) {
    .fifth-section-div {
        margin-bottom: 5rem;
    }

    .fifth-section-div img {
        display: none;
    }

    .fifth-section-left p {
        text-align: center;
    }
}
</style>