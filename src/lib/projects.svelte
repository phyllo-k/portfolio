<main>
    <section id="projects">
        <h2>These are some of my projects</h2>
        <div class="project-grid">
            <a class="project-tile" href="https://codepen.io/phyllo-k/pen/vYJRNag?editors=0111">
                <img src="calculator.png" alt="calculator" />
                <p><span class="brackets">&lt;</span>Calculator<span class="brackets">/&gt;</span></p>
            </a>

            <a class="project-tile" href="https://github.com/phyllo-k/note-lite">
                <img src="note-lite.png" alt="note lite" />
                <p><span class="brackets">&lt;</span>Note Lite<span class="brackets">/&gt;</span></p>
            </a>

            <a class="project-tile" href="https://codepen.io/phyllo-k/pen/GRvmQgd?editors=0111">
                <img src="quote-machine.png" alt="quote machine" />
                <p><span class="brackets">&lt;</span>Quote Machine<span class="brackets">/&gt;</span></p>
            </a>

            <a class="project-tile" href="https://github.com/phyllo-k/euler">
                <img src="euler.jpg" alt="project euler" />
                <p><span class="brackets">&lt;</span>Project Euler<span class="brackets">/&gt;</span></p>
            </a>

        </div>
        <section class="repos">
            <h2>Repositories</h2>
            <a
                href="https://github.com/Phyllo-K"
                title="@PhylloK on GitHub"
                rel="me"
                target="_blank"><i class="fa fa-github-alt fa-2x" />
            </a>
            <a
                href="https://codepen.io/your-work/"
                title="@PhylloK on Codepen"
                rel="me"
                target="_blank"><i class="fab fa-codepen fa-2x"></i>
            </a>
        </section>
    </section>
</main>


<style>
    :global(h2) {
        color: #dff;
        font-size: calc(1vw + 1.5rem);
        margin: 4rem auto;
    }

    .project-grid {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
        gap: 4rem;
        justify-content: space-evenly;
        max-width: 1280px;
        margin: 0 auto;
        padding: 0 3rem;
    }

    .project-tile {
        background: #303848;
        box-shadow: 0 7px 20px 0 rgba(0, 0, 0, 0.2), 0 4px 10px 0 rgba(0, 0, 0, 0.2);
        border-radius: 3px;
    }

    span {
        color: #303848;
        margin: 0 1rem;
    }

    img {
        width: 100%;
        height: calc(100% - 3rem);
        object-fit: cover;
    }
    
    p {
        padding: 0.5rem 0.5rem;
    }

    .repos a {
        display: inline-block;
        margin-bottom: 12rem;
        padding: 0 calc(1rem + 1.5vw);
        position: relative;
        transform: scale(1.5);
    }

    @media (hover: hover) {
        .project-tile:hover {
            box-shadow: 0 7px 20px 0 rgba(150, 150, 226, 0.2), 0 4px 10px 0 rgba(0, 0, 0, 0.2);
        }

        .project-tile:hover span {
            color: #ff7f50;
            transition: color 0.3s ease-out;
        }
    }
</style>