<template>
    <section class="container">
        <div class="container-text">
            <h1>We are here to help you?</h1>
            <p>Suscribe to get newsletters</p>
            <button>Subscribe newsletters</button>
        </div>
        <div class="wave"></div>
    </section>
    <section class="benefits">
        <div>
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
                <path stroke-linecap="round" stroke-linejoin="round" d="M6 12L3.269 3.126A59.768 59.768 0 0121.485 12 59.77 59.77 0 013.27 20.876L5.999 12zm0 0h7.5" />
            </svg>
            <p>Level HTML Template by Tooplate website</p>
            <span>You are allowed to download, edit and use this template for your business or client websites.</span>
            <a href="">Continue reading</a>
        </div>
        <div>
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
                <path stroke-linecap="round" stroke-linejoin="round" d="M6 12L3.269 3.126A59.768 59.768 0 0121.485 12 59.77 59.77 0 013.27 20.876L5.999 12zm0 0h7.5" />
            </svg>
            <p>Level HTML Template by Tooplate website</p>
            <span>You are allowed to download, edit and use this template for your business or client websites.</span>
            <a href="">Continue reading</a>
        </div>
        <div>
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
                <path stroke-linecap="round" stroke-linejoin="round" d="M6 12L3.269 3.126A59.768 59.768 0 0121.485 12 59.77 59.77 0 013.27 20.876L5.999 12zm0 0h7.5" />
            </svg>
            <p>Level HTML Template by Tooplate website</p>
            <span>You are allowed to download, edit and use this template for your.</span>
            <a href="">Continue reading</a>
        </div>
    </section>
</template>

<style scoped>
.container-text {
    padding-top: 30px;
    display: flex;
    flex-direction: column;
    align-items: center;
    color: white;
}

.container-text h1 {
    font-size: 3rem;
    margin-bottom: 20px;
}

.container-text p {
    font-size: 1.4rem;
    margin-bottom: 30px;
}

.container-text button {
    border: 1px solid white;
    background: var(--brand-color);
    padding: 13px;
    color: white;
}
.container {
  position: relative;
  background: var(--brand-color);
  height: 50vh;
}

.wave {
  position: absolute;
  height: 70px;
  width: 100%;
  background: var(--brand-color);
  bottom: 0;
}

.wave::before, .wave::after {
  content: "";
  display: block;
  position: absolute;
  border-radius: 100% 50%;
}

.wave::before {
  width: 55%;
  height: 109%;
  background-color: #fff;
  right: 0.1%;
  top: 60%;
}
.wave::after {
  width: 55%;
  height: 100%;
  background-color: var(--brand-color);
  left: -1.5%;
  top: 40%;
}

/* BENEFITS SECCION */

.benefits {
    display: flex;
    justify-content: space-between;
    margin: 100px auto;
    width: 70%;
}

.benefits svg{
    width: 60px;
    color: var(--brand-color);
}

.benefits div{
    display: flex;
    flex-direction: column;
    align-items: center;    
    justify-content: space-between;
    height: 256px;
    width: 280px;
    margin-bottom: 100px;
}

.benefits div p {
    color: var(--brand-color);
    font-size: 1.3rem;
    font-weight: 800;
}

.benefits span {
    color: gray;
}

.benefits a {
    color: var(--brand-color);
    text-decoration: none;
}
</style>