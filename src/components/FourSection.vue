<template>
    <section class="four-section d-flex justify-content-center align-items-center">
        <div class="four-section-div d-flex flex-column align-items-center justify-content-center gap-2">
            <h1>Vamos começar seu projeto?</h1>
            <p>Fale com um consultor e tire sua idéia do papel.</p>
            <a href="#seventh-section"><button>Entrar em contato</button></a>
        </div>
    </section>
</template>

<script>
export default {

}
</script>

<style>
.four-section {
    width: 100%;
    background-image: url(/banner.png);
    background-position: center;
    background-size: cover;
    background-repeat: no-repeat;
    color: white;
    padding: 5rem;
    margin-bottom: 5rem;
    text-align: center;
}

.four-section div {
    max-width: 1250px;
}

.four-section button {
    background-color: #FFDD33;
    border-radius: 10px;
    height: 3rem;
    width: 11rem;
    color: #0F3FD3;
    text-transform: uppercase;
    border-style: none;
    font-family: 'Raleway', sans-serif;
    font-weight: 800;
    padding: 0.5rem;
    text-align: center;
    transition: transform 0.2s ease;
}

.four-section button:hover {
    transform: scale(1.1);
}
</style>