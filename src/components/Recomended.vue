<template>
    <section class="recomended-section">
        <div class="recomended-container">
            <div class="img-container">
                    <div class="img-info">
                        <img src="https://www.tooplate.com/templates/2095_level/img/img-01.jpg" alt="">
                        <h2 class="img-text">NUNC IN  FELIS ALIQUET METUS LUCTUS IACULIS</h2>
                        <p>Lorem ipsum dolor sit amet.kadnklsadnaskldsad Lorem ipsum dolor sit amet consectetur adipisicing elit. Reiciendis, dolore!</p>
                        <button>Get more info</button>
                    </div>
                    <div class="img-info">
                        <img src="https://www.tooplate.com/templates/2095_level/img/img-01.jpg" alt="">
                        <h2 class="img-text">NUNC IN  FELIS ALIQUET METUS LUCTUS IACULIS</h2>
                        <p>Lorem ipsum dolor sit amet.kadnklsadnaskldsad Lorem ipsum dolor sit amet consectetur adipisicing elit. Reiciendis, dolore!</p>
                        <button>Get more info</button>
                    </div>
            </div>
            <div class="cards-seccion">
                <div class="recomend-text">
                <h2>Recomended Places</h2>
                <p>lorem ipsum siament solflmda</p>
                </div>
                <div>
                    <div class="cards">
                        <img src="https://www.tooplate.com/templates/2095_level/img/tn-img-01.jpg" alt="">
                        <p>EUROPE</p>
                    </div>
                    <div class="cards">
                        <img src="https://www.tooplate.com/templates/2095_level/img/tn-img-01.jpg" alt="">
                        <p>EUROPE</p>
                    </div>
                    <div class="cards">
                        <img src="https://www.tooplate.com/templates/2095_level/img/tn-img-01.jpg" alt="">
                        <p>EUROPE</p>
                    </div>
                    <div class="cards">
                        <img src="https://www.tooplate.com/templates/2095_level/img/tn-img-01.jpg" alt="">
                        <p>EUROPE</p>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<style scoped>
    .recomended-section {
        padding-top: 20px;
        background: rgb(216, 214, 214);
        width: 100%;
        height: 600px;
    }
    
    .recomended-container {
        display: grid;
        grid-template-columns: repeat(2,1fr);
        align-content: center;
        gap: 70px;
        width: 80%;
        margin: 0 auto;
    }

    .img-container {
        display: grid;
        grid-template-columns: repeat(2, 1fr);
        gap: 50px;
        width: 100%;
    }

    .img-info {
        width: 350px;
        height: 300px;
    }

    .img-info img {
        width: 350px;
    }

    .img-text {
        padding-bottom: 10px;
        font-size: 1.4rem;
    }

    .img-info p {
        margin-bottom: 20px;
    }
    .img-info button {
        background: var(--brand-color);
        color: white;
        border: none;
        width: 100%;
        height: 40px;
    }

    .cards {
        margin-top: 20px;
        display: flex;
        align-items: center;
    }

    .cards img {
        margin-right: 10px;
    }

    .recomend-text {
        background: var(--brand-color);
        color: white;
        width: 280px;
        height: 70px;
        padding: 10px
    }
</style>