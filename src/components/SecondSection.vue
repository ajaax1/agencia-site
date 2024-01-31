<template>
    <section class="d-flex justify-content-center align-items-center second-section">
        <div  class="d-flex justify-content-between align-items-center">
            <img v-motion-slide-visible-once-top src="../assets/img/LOGO1.png" alt="">
            <img v-motion-slide-visible-once-top src="../assets/img/LOGO2.png" alt="">
            <img v-motion-slide-visible-once-top src="../assets/img/LOGO4.png" alt="">
            <img v-motion-slide-visible-once-top src="../assets/img/LOGO5.png" alt="">
        </div>
    </section>
</template>

<script>
export default {

}
</script>

<style>
.second-section {
    background-color: white;
    min-height: 15rem;
    width: 100%;
    margin-bottom: 5rem;
}

.second-section div {
    background-color: white;
    flex-wrap: wrap;
    justify-content: center !important;
    max-width: 1250px;
}

.second-section div img {
    transition: transform 0.3s ease;
}

.second-section div img:hover {
    transform: scale(1.1);
}

@media only screen and (max-width: 520px) {
    .second-section div {
        width: 100%;
        justify-content: center !important;
    }
}
</style>