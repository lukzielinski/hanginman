<script lang="ts">
    import Router from 'svelte-spa-router'

    const routes = {}
    const unusedItem = 0
</script>

<svelte:head>
    <link rel="icon" type="image/svg" href="/assets/robotIcon.svg" />
    <title>Hang Man</title>
</svelte:head>

<main>
    <Router {routes} />
</main>

<style lang="less">
    main {
        text-align: center;
    }
</style>
