<nav id="navbar">
    <a href="#hero">About</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
</nav>

<style>
    #navbar {
        background: #222733;
        box-shadow: 0 7px 20px 0 rgba(0, 0, 0, 0.2),
            0 4px 10px 0 rgba(0, 0, 0, 0.2);
        font-size: 1.2rem;
        position: fixed;
        top: 0;
        left: 0;
        width: 100vw;
        height: 4rem;
        display: flex;
        justify-content: center;
        align-items: center;
        z-index: 99;
    }

    a {
        display: inline-block;
        padding: 0 calc(2vw + 1rem);
        line-height: 3em;
        position: relative;
    }

    @media (hover: hover) {
        a:hover {
            transform: scale(1.1);
        }
    }
</style>
