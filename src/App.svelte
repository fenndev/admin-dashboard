<script>
    import Sidebar from './components/Sidebar/Sidebar.svelte';
    import Header from './components/Header/Header.svelte';
    import Body from './components/Body.svelte';
</script>

<div class="container">
    <Sidebar />
    <Header />
    <Body />
</div>

<style>
    :global(body) {
        height: 100svh;
        margin: 0;
        padding: 0;
        box-sizing: border-box;
    }
    .container {
        min-height: 100%;
        background-color: lightgray;
        display: grid;
        grid-template-columns: 15vw 1fr;
        grid-template-rows: 20vh 1fr;
    }
</style>
