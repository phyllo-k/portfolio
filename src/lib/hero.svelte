<header id="hero">
    <h1>Hi, I am Firo.</h1>
    <p>a web developer</p>
</header>

<style>
    #hero {
        display: flex;
        flex-flow: column wrap;
        align-items: center;
        justify-content: center;
        height: 100vh;
        font-size: 5vw;
    }

    h1 {
        animation: flash 5s forwards;
        font-family: "Italianno", cursive;
        font-size: 2.5em;
        position: relative;
    }

    p {
        animation: fly-left 3s forwards;
        animation-delay: 2s;
        color: #fcf;
        opacity: 0;
        position: relative;
    }

    @keyframes flash {
    0% {
        opacity: 0;
    }

    100% {
        opacity: 1;
    }
}

@keyframes fly-left {
    0% {
        left: 100vw;
        opacity: 0;
    }
    100% {
        left: 0px;
        opacity: 1;
    }
}
</style>