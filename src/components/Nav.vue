<template>
    <nav>
        <div>
            <img src="https://www.tooplate.com/templates/2095_level/img/logo.png" alt="">
            <h1>Level</h1>
        </div>
        <ul>
            <li>Home</li>
            <li>Portfolio</li>
            <li>Blog entries</li>
            <li>Contact us</li>
        </ul>
    </nav>
</template>

<style scoped>
    nav {
        display: flex;
        align-items: center;
        justify-content: space-between;
        width: 95%;
        height: 119px;
        max-width: 960px;
        margin-left: 150px;
    }

    nav img {
        width: 60px;
        margin-right: 15px;
    }

    nav ul {
        display: flex;
        height: 150px;
        width: 450px;
        align-items: center;
        justify-content: space-between;
        list-style: none;
    }

    nav ul li {
        border-right: 1px solid rgb(204 204 204);
        padding: 50px 10px;
    }

    nav div {
        display: flex;
        align-items: center;
    }

    nav ul li:first-child {
        background: var(--brand-color);
        color: white;
    }

    nav ul li:hover {
        background: var(--brand-color);
        color: white;
    }
</style>