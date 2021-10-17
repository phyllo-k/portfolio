<main>
    <section id="projects">
        <h2>These are some of my projects</h2>
        <div class="project-grid">
            <a class="project-tile" href="https://github.com/Phyllo-K/Note-Lite">
                <img src="note-lite.png" alt="note lite" />
                <p><span class="brackets">&lt; </span>Note Lite<span class="brackets"> /></span></p>
            </a>


            <a class="project-tile" href="https://codepen.io/phyllo-k/pen/ZEJzpzY?editors=1100">
                <img src="js-doc.png" alt="js doc" />
                <p><span class="brackets">&lt; </span>JS Documentation<span class="brackets"> /></span></p>
            </a>

            <a class="project-tile" href="https://github.com/Phyllo-K/Euler">
                <img src="euler.jpg" alt="project euler" />
                <p><span class="brackets">&lt; </span>Project Euler<span class="brackets"> /></span></p>
            </a>

        </div>
        <a href="https://github.com/Phyllo-K" class="projects-link" target="_blank">Show all</a>
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
        grid-gap: 4rem;
        max-width: 1280px;
        margin: 0 auto;
    }

    a {
        background: #303848;
        box-shadow: 0 7px 20px 0 rgba(0, 0, 0, 0.2), 0 4px 10px 0 rgba(0, 0, 0, 0.2);
        border-radius: 3px;
    }

    a:hover {
        box-shadow: 0 7px 20px 0 rgba(150, 150, 226, 0.2), 0 4px 10px 0 rgba(0, 0, 0, 0.2);
    }

    .project-tile span {
        color: #303848;
    }

    .project-tile:hover span {
        color: #ff7f50;
        transition: color 0.3s ease-out;
    }

    img {
        width: 100%;
        height: calc(100% - 3rem);
        object-fit: cover;
    }
    
    p {
        padding: 0.5rem 0.5rem;
    }

    .projects-link {
        margin: 4rem auto;
        padding: 1rem 2rem;
        display: inline-block;
    }
</style>