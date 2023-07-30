<script lang="ts">
    export let title = 'Button'
</script>

<button class="button-34" role="button">
    <slot>{title}</slot>
</button>

<style lang="less">
    .button-34 {
        background: #5e5df0;
        border-radius: 999px;
        box-shadow: #5e5df0 0 10px 20px -10px;
        box-sizing: border-box;
        width: 50vw;
        color: #ffffff;
        cursor: pointer;
        font-family: Inter, Helvetica, 'Apple Color Emoji', 'Segoe UI Emoji', NotoColorEmoji, 'Noto Color Emoji', 'Segoe UI Symbol',
            'Android Emoji', EmojiSymbols, -apple-system, system-ui, 'Segoe UI', Roboto, 'Helvetica Neue', 'Noto Sans', sans-serif;
        font-size: 16px;
        font-weight: 700;
        line-height: 24px;
        opacity: 1;
        outline: 0 solid transparent;
        padding: 8px 18px;
        user-select: none;
        -webkit-user-select: none;
        touch-action: manipulation;
        word-break: break-word;
        border: 0;
        margin: 20px;
    }
    .button-34:hover {
        background: #4c4bef;
        box-shadow: #4c4bef 0 10px 20px -10px;
    }
    .button-34:active {
        background: #3a39e8;
        box-shadow: #3a39e8 0 10px 20px -10px;
    }
    .button-34:focus {
        box-shadow: #5e5df0 0 0 0 3px;
    }
</style>
