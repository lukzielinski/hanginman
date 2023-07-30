<script lang="ts">
    import Menu from './views/Menu.svelte'

    const routes = {}
</script>

<svelte:head>
    <link rel="icon" type="image/svg" href="/assets/robotIcon.svg" />
    <title>Hang Man</title>
</svelte:head>

<main>
    <!-- <Router {routes} /> -->
    <Menu />
</main>

<style lang="less">
    /* Wszystkie elementy na stronie będą zajmować 100vh */
    * {
        margin: 0;
        padding: 0;
        box-sizing: border-box !important;
    }
    main {
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        margin: 0 auto;
        height: 100vh;
        box-sizing: border-box !important;
    }
    :global(:root) {
        margin: 0;
        padding: 0;
    }
</style>
