<script>
    const year = new Date().getFullYear();
</script>

<footer>
    <section id="contact">
        <h2>Let's work together...</h2>
        <a
            href="https://github.com/Phyllo-K"
            title="@PhylloK on GitHub"
            rel="me"
            target="_blank"><i class="fa fa-github-alt fa-2x" /></a
        >
        <a
            href="https://twitter.com/phyllo_k"
            title="@PhylloK on Twitter"
            rel="me"
            target="_blank"><i class="fab fa-twitter fa-2x" /></a
        >
        <a
            href="https://www.linkedin.com/in/firokong/"
            title="@firo on LinkedIn"
            rel="me"
            target="_blank"><i class="fab fa-linkedin-in fa-2x" /></a
        >
        <a
            href="mailto:firo.kong@gmail.com"
            title="@PhylloK at Gmail"
            rel="me"
            target="_blank"><i class="fas fa-envelope fa-2x" /></a
        >
    </section>
    <hr />
    <p class="copyright">© {year} Firo Kong</p>
</footer>

<style>
    footer {
        font-size: 1rem;
        padding: 12rem 0 3rem 0;
    }

    footer hr {
        color: red;
        margin: 2rem auto;
    }

    a {
        display: inline-block;
        margin-bottom: 12rem;
        padding: 0 calc(1rem + 1.5vw);
        position: relative;
        transform: scale(1.5)
    }

    a:hover {
        animation: links 0.3s forwards;
    }

    @keyframes links {
        0% {
            top: 0;
        }
        100% {
            top: 1rem;
        }
    }
</style>
