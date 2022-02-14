<script>
    import Subtitle from '../components/Subtitle.svelte'
    import Contact from '../components/contact.svelte'
    import Title from '../components/Title.svelte'
</script>

<svelte:head>
    <title>Simon Aunér - auner.se</title>
</svelte:head>

<main class="main">
    <div>
        <Title>www.auner.se</Title>
        <Subtitle>Simon Aunér</Subtitle>
        <Contact />
    </div>
</main>

<style>
    .main {
        min-height: 100vh;
        display: flex;
        align-items: center;
        justify-content: center;
    }
</style>
