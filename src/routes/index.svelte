<script>
    import Nav from "$lib/nav.svelte";
    import Hero from "$lib/hero.svelte";
    import Projects from "$lib/projects.svelte";
    import Footer from "$lib/footer.svelte";
</script>

<svelte:head>
    <title>Firo Kong | Portfolio</title>
    <script
        src="https://kit.fontawesome.com/c1d1113afa.js"
        crossorigin="anonymous"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
        href="https://fonts.googleapis.com/css2?family=Cutive+Mono&family=Italianno&display=swap"
        rel="stylesheet"
    />
</svelte:head>

<Nav />
<Hero />
<Projects />
<Footer />

<style>
    @supports (padding: max(0px)) {
        body, header, footer {
            padding-left: min(0vmin, env(safe-area-inset-left));
            padding-right: min(0vmin, env(safe-area-inset-right));
        }
    }

    :global(*) {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
    }

    :global(body) {
        background: #121212;
        color: #eee;
        font-family: "Cutive Mono", monospace;
        text-align: center;
        overflow-x: hidden;
        user-select: none;
    }

    :global(section) {
        padding: 2em 0;
    }

    :global(a) {
        color: #eee;
        font-size: 1.2rem;
        text-decoration: none;
    }
</style>
