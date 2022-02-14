<script>
    import Subtitle from '../components/Subtitle.svelte'
    import Contact from '../components/contact.svelte'
    import Title from '../components/Title.svelte'
</script>

<svelte:head>
    <title>Simon Aunér - auner.se</title>
</svelte:head>

<main class="container">
    <div class="header">
        <Title>www.auner.se</Title>
        <Subtitle>Simon Aunér</Subtitle>
        <Contact />
    </div>
</main>

<style>
    .container {
        padding: 3rem;
        margin: 0 auto;
    }

    @media (min-width: 476px) {
        .container {
            padding: 4rem;
            max-width: 476px;
        }
    }

    @media (min-width: 768px) {
        .container {
            padding: 5rem;
            max-width: 768px;
        }
    }

    @media (min-width: 1200px) {
        .container {
            padding: 6rem;
            max-width: 1200px;
        }
    }

    @media (min-width: 1600px) {
        .container {
            padding: 9rem;
            max-width: 1600px;
        }
    }
</style>
