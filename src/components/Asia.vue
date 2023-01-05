<template>
    <section class="asia-section">
        <div class="asia-text">
            <h1>ASIA</h1>
            <p>Singapoure</p>
        </div>
        <div class="asia-articles">
            <div class="articles-article">
                <img src="https://www.tooplate.com/templates/2095_level/img/img-03.jpg" alt="">
                <div>
                    <h3>Suspedisse vel est libero sem halleus ac</h3>
                    <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Vitae, impedit.</p>
                    <a href="">Continue reading</a>
                </div>
            </div>
            <div class="articles-article">
                <img src="https://www.tooplate.com/templates/2095_level/img/img-03.jpg" alt="">
                <div>
                    <h3>Suspedisse vel est libero sem halleus ac</h3>
                    <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Vitae, impedit.</p>
                    <a href="">Continue reading</a>
                </div>
            </div>
            <div class="articles-article">
                <img src="https://www.tooplate.com/templates/2095_level/img/img-03.jpg" alt="">
                <div>
                    <h3>Suspedisse vel est libero sem halleus ac</h3>
                    <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Vitae, impedit.</p>
                    <a href="">Continue reading</a>
                </div>
            </div>
        </div>
    </section>
</template>

<style scoped>
    .asia-text {
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
    }

    .asia-text h1{
        font-size: 3rem;
    }

    .asia-text p {
        font-size: 2rem;
        color: var(--brand-color);
    }
    .asia-section {
        display: grid;
        grid-template-columns: repeat(2, 1fr);
        width: 80%;
        margin-top: 50px;
    }

    .articles-article {
        display: flex;
        align-items: center;
        padding-bottom: 10px;
    }

    .articles-article img {
        padding-right: 10px;
        width: 250px;
    }

    .articles-article p {
        margin-bottom: 10px;
    }

    .articles-article a {
        text-decoration: none;
        color: var(--brand-color);
    }
</style>