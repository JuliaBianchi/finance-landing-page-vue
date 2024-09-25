<template>
    <section class="content-section">
        <container class="content-text">
            <h1 class="content-text-title">Mutual Investment</h1>
            <p class="content-text-description">At Finance we care about your future. We help you invest the way you want. So you can relax, have fun and let your fund grow.</p>
            <a class="content-link" href="https://www.linkedin.com/in/juliaspaderbianchi/">Learn more</a>
        </container>
    
        <img src="../assets/images/Revenue-bro 1 (1).png" alt="">
  
    </section>
    
</template>

<style>

* {
    padding: 0;
    margin: 0;
}

.content-section {
    height: 80vh;
    margin: 0% 10%;
    display: flex;
    justify-content: space-between;
  
}

.content-text {
    display: flex;
    flex-direction: column;
    align-self: center;
    gap: 40px;
}

.content-text-title {
    font-size: 2.8rem;
    color: #D2D2D2;
}

.content-text-description {
    font-size: 1.6rem;
    color: #A9A9A9;
}

.content-link {
    text-decoration: none;
    color: white;
    background-color: #27AE60;
    width: 8em;
    font-size: 1.6rem;
    font-weight: bold;
    border-radius: 30px;
    text-align: center;
    padding: 0.5em;
}

@media(max-width: 450px){
    .content-section{
        flex-direction: column-reverse;
        padding-bottom: 5em;
        height: 100vh;
    }

    .content-text-title{
        padding-top: 4rem;
        font-size: 2.5rem;
    }

    .content-text-description {
        font-size: 1.5rem;
    }

    .content-link{
        width: 6em;
        font-size: 1.2rem;
    }
}

@media(max-width: 768px){
    .content-section img{
        height: 300px;
        align-self: center;
    }

    .content-text-title{
        padding-top: 4rem;
        font-size: 2.0rem;
    }

    .content-text-description {
        font-size: 1.2rem;
    }

    .content-link{
        width: 6em;
        font-size: 1.2rem;
    }

}


</style>