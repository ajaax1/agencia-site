<template>
    <section id="first-section" class="first-section d-flex justify-content-center align-items-center">
        <div v-motion-fade >
            <h1>Promova experiências aos seus clientes</h1>
            <p>E veja resultados expressivos dia após dia</p>
            <img src="../assets/img/macbook mockup.svg" alt="">
        </div>
    </section>
</template>

<script>
export default {

}
</script>

<style>
.first-section {
    background-color: #0F3FD3;
    color: white;
    margin-bottom: 5rem;
    background-image: url(/banner.png);
    background-position: center;
    background-size: cover;
    background-repeat: repeat;
    text-align: center;
    padding-top: 5rem;
}

.first-section img {
    width: 600px;
    height: 400px;
}

.first-section div {
    display: flex;
    justify-items: center;
    align-items: center;
    flex-direction: column;
    max-width: 1250px;
    margin-bottom: 3rem;
    padding-top: 3rem;
}

@media only screen and (max-width: 620px) {
    .first-section img {
        width: 90%;
        height: 80%;
    }

}
</style>