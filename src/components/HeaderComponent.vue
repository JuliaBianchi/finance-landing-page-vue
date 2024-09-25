<template>
    <nav class="nav-bar">
        <container class="social-media">
            <a class="social-media-link" href="#"><img src="../assets/icons/linkedin.svg"></a>
            <a class="social-media-link" href="#"><img src="../assets/icons/github.svg"></a>
            <a class="social-media-link" href="#"><img src="../assets/icons/mail.svg"></a>
        </container>

        <container class="logo">
            <img class="logo-image" alt="Imagem da logo da empresa" src="../assets/images/logo.svg" >
        </container>

        <container class="options-menu">
            <a class="social-media-link" href="#"><img src="../assets/icons/menu.svg"></a>
        </container>
    </nav>
</template>

<style>

* {
    padding: 0;
    margin: 0;
    background-color: #1D1D1D;
}

.nav-bar {
    display: flex;
    justify-content: space-between;
    padding:  1.6em;
}

.social-media {
    display: flex;
    gap: 50px;
}

@media(max-width: 425px){
    .nav-bar {
        height: 200px;
        padding: 1rem;
    }

    .social-media {
        gap: 10px;
    }
}

@media(max-width: 768px){
    .social-media {
        gap: 40px;
    }
}

@media(max-width: 375px){
    .social-media {
        gap: 10px;
    }
}

</style>
