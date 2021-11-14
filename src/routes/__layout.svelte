<!-- src/routes/__layout.svelte -->
<nav>
    <a href="/">Start</a>
    <a href="/cv">CV</a>
    <a href="/about">About this site</a>
</nav>

<main>
    <slot />
</main>

<div class="footer">
    <p class="author">Simon Aunér <br /> November, 2021</p>

    <a href="mailto:simonauner@gmail.com">simonauner@gmail.com</a>
    |
    <a href="https://linkedin.com/in/simonauner">LinkedIn</a>
    |
    <a href="https://github.com/simonauner">GitHub</a>
</div>

<style>
    nav,
    div,
    main {
        min-width: 20rem;
        max-width: 40rem;
        margin-left: auto;
        margin-right: auto;
    }

    nav {
        margin-top: 1rem;
        margin-bottom: 2rem;
    }
    .footer {
        text-align: center;
        margin-top: 4rem;
        margin-bottom: 4rem;
    }

    @media print {
        nav,
        .footer {
            visibility: hidden;
        }
    }
</style>
