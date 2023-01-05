<template>
    <section class="contact">
        <section>
                <section class="zxz">
        <div class="section__container1">
                <img src="../icons/localitation.svg" alt="/">
                <input type="text" placeholder="Type your destination...">

                <img src="../icons/calendar.svg" alt="/">
                <input type="text" placeholder="Check in">

                <img src="../icons/calendar.svg" alt="/">
                <input type="text" placeholder="Check Out">
        </div>
        <div class="section__container2">
            <img src="../icons/user.svg" alt="/" class="mdf">
            <input type="text" placeholder="Adult">
            <img src="../icons/arrow.svg" alt="/" class="arrow">
    
            <img src="../icons/user.svg" alt="/" class="mdf mdf2">
            <input type="text" placeholder="Children">
            <img src="../icons/arrow.svg" alt="/" class="arrow">
    
            <img src="../icons/bed.svg" alt="/" class="mdf">
            <input type="text" placeholder="Room">
            <img src="../icons/arrow.svg" alt="/" class="arrow">
            
            <a href="#" class="btn">check availability</a>
        </div>
        <div class="section__texts">
            <p>Those are the little things that make you great.</p>
            <a href="#">Need Help?</a>
        </div>
    </section>
        </section>
    </section>
</template>


<style scoped>
    .contact {
        background-image: url('https://live.mrf.io/statics/i/ps/www.muylinux.com/wp-content/uploads/2014/09/mountain1.jpg?width=1200&enable=upscale');
        background-repeat: no-repeat;
        background-size: cover ;
        width: 100%;
        height: 506px;
        padding-top: 77px;
    }


.zxz{
    margin-top: 200px;
    width: 70%;
    margin: 0 auto;
    background-color: #fff;
    border: 1px solid #000;
    padding: 30px 40px;
}
.section__container1{
    margin-bottom: 20px;
}

.section__container1 input{
    position: relative;
    outline: none;
    border: 1px solid #000;
    padding: 0.75rem 0.75rem 0.75rem 45px;
    width: 30%;
 
}

.section__container1 img{
    position: absolute;
    margin-left: 10px;
    z-index: 1;
}


.section__container2 input{
    position: relative;
    outline: none;
    border: 1px solid #000;
    padding: 0.75rem 0.75rem 0.75rem 45px;
    width: 23%;
    margin-bottom: 30px;
}

.mdf{
    position: absolute;
    margin-left: 10px;
    z-index: 1;
}

.arrow{
    position: absolute;
    width: 10px;
    margin-left: -30px;
    z-index: 1;
    cursor: pointer;
}

.mdf2{
    width: 10px;
}


.btn{
    width: 23%;
    background-color: #d53239;
    border-color: #d53239;
    color: #fff;
    text-decoration: none;
    padding: 14px 38px;
    text-transform: uppercase;
    font-size: 10px;
    font-weight: bold;
    transition: 0.2s;
}

.btn:hover{
    background-color: rgb(198, 7, 7);
}

.section__texts{
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-bottom: 16px;
}

.section__texts a{
    margin-right: 80px;
    font-weight: bold;
    font-size: 13px;
    color: #d53239;
    text-decoration: none;
}

.section__texts p{
    font-size: 13px;
    font-weight: bold;
}
</style>