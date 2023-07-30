<script lang="ts">
    const routes = {}
</script>

<svelte:head>
    <link rel="icon" type="image/svg" href="/assets/robotIcon.svg" />
    <title>Hang Man</title>
</svelte:head>

<main>
    <!-- <Router {routes} /> -->
    <!-- <Menu /> -->
</main>

<style lang="less">
    html,
    body {
        height: 100%;
        margin: 0;
        padding: 0;
    }

    /* Wszystkie elementy na stronie będą zajmować 100vh */
    * {
        box-sizing: border-box;
        height: 100vh;
        margin: 0;
        padding: 0;
    }
    main {
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        height: 100vh;
        margin: 0 auto;
        border: 10px solid red;
    }
    :global(:root) {
        margin: 0;
        padding: 0;
    }
</style>
