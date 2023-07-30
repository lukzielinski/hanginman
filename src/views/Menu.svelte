<script lang="ts">
    import executioner from '../../public/assets/executioner.png'
    import Button from './elements/Button.svelte'
</script>

<div class="menu-container">
    <div class="executioner-container">
        <img class="executioner" src={executioner} alt="executioner" />
    </div>
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
        display: grid;
        grid-template-rows: 40% 55%;
        justify-content: center;
        align-items: center;
    }
    .buttons {
        height: 100%;
        width: 100%;
        display: flex;
        flex-direction: column;
        justify-content: space-evenly;
        align-items: center;
    }
    .executioner {
        height: 200px;
        width: 200px;
    }
    .executioner-container {
        width: 100%;
        display: flex;
        justify-content: center;
    }
</style>
