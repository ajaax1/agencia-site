<template>
    <header class="d-flex justify-content-center align-items-center">
        <div class="header-div d-flex justify-content-between align-items-center">
            <img class="logo" src="../assets/img/logoagência.png" alt="">
            <nav class="d-flex align-items-center gap-4 first-nav">
                <ul class="list d-flex gap-3 align-items-center">
                    <li><a class="active" href="">Início</a></li>
                    <li><a class="active" href="">Por que nós?</a></li>
                    <li><a class="active" href="">Depoimentos</a></li>
                </ul>
                <button class="contact-button">Entre em contato</button>
            </nav>
            <span @click="switchIcon" class="menu material-symbols-outlined notranslate ">
                {{ menu }}
            </span>
        </div>
        <nav :class="{ 'second-nav': true, 'nav-animation': isNavAnimation }">
            <ul>
                <li><a class="" href="">Início</a></li>
                <li><a class="" href="">Por que nós?</a></li>
                <li><a class="" href="">Depoimentos</a></li>
            </ul>
        </nav>
    </header>
</template>

<script>
export default {
    data() {
        return {
            menu: "menu",
            isNavAnimation:false
        };
    },
    methods: {
        switchIcon() {
            if (this.menu === "menu") {
                this.menu = "close";
                this.isNavAnimation = true;

            } else {
                this.menu = "menu";
                this.isNavAnimation = false;
            }
        }
    }
};
</script>


<style>
header {
    background-color: #255AFF;
    color: white;
    padding: 1rem;
    position: fixed;
    width: 100%;
    z-index: 1000;
}

.header-div {
    width: 1250px;
}

nav ul {
    height: 100%;
}

.contact-button {
    background-color: #0F3FD3;
    padding: 0.5em;
    border-radius: 10px;
    transition: background-color 0.3s ease;
    border-style: none;
    color: white;
}

.contact-button:hover  {
    background-color: #0d34a7;
}

a {
    position: relative;
    color: white;
}

li a.active::before {
    content: "";
    position: absolute;
    bottom: -1px;
    width: 0px;
    border-radius: 2px;
    height: 1.5px;
    background-color: #FFDD33;
    transition: width 0.3s ease;
}

li a.active:hover::before {
    width: 100%;
}

.second-nav {
    background-color: #255AFF;
    width: 100%;
    height: 0px;
    transition: height 0.3s;
    overflow: hidden;
}

.nav-animation {
    height: 5rem;
}

.menu {
    cursor: pointer;
}

@media only screen and (max-width: 1134px) {
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

@media only screen and (max-width: 740px) {
    .first-nav {
        display: none !important;
    }

    header {
        flex-direction: column;
    }

    .header-div {
        width: 100%;
        margin-bottom: 1rem;
    }

}

@media only screen and (min-width: 741px) {
    .menu {
        display: none !important;
    }
    .second-nav{
        display: none;
    }

}
@media only screen and (max-width: 300px) {
    .logo{
        width: 13rem;
    }
}
</style>