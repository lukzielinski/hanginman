<script lang="ts">
    import Button from './elements/Button.svelte'
</script>

<div class="menu-container">
    <div class="buttons">
        <Button title="Play" />
        <Button title="Options" />
    </div>
</div>

<style lang="less">
    .menu-container {
        height: 100%;
        width: 100%;
        background-image: linear-gradient(-40deg, #0f0c29, #302b63, #24243e);
        background-size: 130% 130%;
        margin: 0;
        padding: 0;
    }
    .buttons {
        height: 100%;
        width: 100%;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
    }
</style>
