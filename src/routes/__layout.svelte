<!-- src/routes/__layout.svelte -->
<nav>
    <a href="/">Start</a>
    <a href="cv">CV</a>
    <a href="about">About this site</a>
</nav>

<div>
    <slot />
</div>

<div>
    Contact: <a href="mailto:simonauner@gmail.com">simonauner@gmail.com</a>
    |
    <a href="https://linkedin.com/in/simonauner">LinkedIn</a>
    |
    <a href="https://github.com/simonauner">GitHub</a>
</div>

<style>
    nav,
    div,
    slot {
        min-width: 500px;
        max-width: 800px;
        margin-left: auto;
        margin-right: auto;
    }

    nav {
        margin-top: 16px;
        margin-bottom: 32px;
    }
    div {
        margin-top: 64px;
        margin-bottom: 16px;
    }
</style>
