<script context="module">
    export const prerender = true
</script>

<script lang="ts">
    let value: number = 0;

    let increaseValue = () => ++value;
</script>

<h1>Value {value}</h1>

<button on:click={increaseValue}>Increase</button>