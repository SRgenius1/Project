<template>
    <footer>
        <form>
            <input placeholder=" Name" type="text">
            <input placeholder=" Email" type="text">
            <input placeholder=" Subject" type="text">
            <textarea placeholder=" Message"></textarea>
            <button>Send Message now</button>
        </form>
    </footer>
</template>

<style scoped>
    footer {
        background-image: url('https://live.mrf.io/statics/i/ps/www.muylinux.com/wp-content/uploads/2014/09/mountain1.jpg?width=1200&enable=upscale');
        background-repeat: no-repeat;
        background-size: cover;
        height: 500px;
        display: flex;
        justify-content: center;
        align-items: center;
    }

    form {
        display: flex;
        justify-content: space-between;
        height: 400px;
        flex-direction: column;
        width: 430px;
        background: white;
        padding: 40px;
    }

    form input {
        background: rgb(194, 190, 190);
        height: 40px;
        border: none;
    }

    form input::placeholder {
        color: white;
    }

    form textarea {
        background: rgb(196, 191, 191);
        border: none;
    }

    form button {
        background: var(--brand-color);
        border: none;
        color: white;
        padding: 16px;
    }
</style>