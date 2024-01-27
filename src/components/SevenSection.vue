<template>
    <section id="seventh-section" class="seventh-section d-flex justify-content-center">
        <div class="seventh-section-div d-flex flex-column justify-content-center ">
            <h1>Entre em contato</h1>
            <form class="d-flex flex-column justify-content-center align-items-center" action="">
                <input placeholder="  Name" type="text">
                <input placeholder="  Email" type="text">
                <textarea placeholder="  Message" name="" id="" cols="30" rows="10"></textarea>
                <button>Enviar</button>
            </form>
        </div>
    </section>
</template>
 
<script>
export default {

}
</script>
 
<style>
.seventh-section {
    width: 100%;
}

.seventh-section div {
    width: 1250px;
    padding: 1rem;
}

.seventh-section h1 {
    color: #000000;
    font-family: 'Raleway', sans-serif;
    font-weight: 800;
    text-align: center;
    margin-bottom: 3rem;
}

form {
    padding: 1rem;
    gap: 1rem;
}

input {
    max-width: 30rem;
    width: 100%;
    border-radius: 5px;
    height: 3rem;
    border-style: solid;
    border-width: 1px;
    border-color: #C3CCE8;
    color: #C3CCE8;
}

textarea {
    max-width: 30rem;
    width: 100%;
    border-radius: 5px;
    height: 10rem;
    border-style: solid;
    border-width: 1px;
    border-color: #C3CCE8;
    color: #C3CCE8;
    padding-top: 0.5rem;
}

form button {
    background-color: #0F3FD3;
    padding: 0.5em;
    border-radius: 10px;
    transition: background-color 0.3s ease;
    border-style: none;
    color: white;
    max-width: 30rem;
    width: 100%;
}

form button:hover {
    background-color: #0d34a7;
}
</style>