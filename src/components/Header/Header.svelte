<script>
    import UserDisplay from './UserDisplay.svelte';
    import Search from './Search.svelte';
    import Greeter from './Greeter.svelte';
    import ActionButtons from './ActionButtons.svelte';
</script>

<header>
    <div class="top">
        <Search />
        <div class="account">
            <Greeter />
            <UserDisplay />
        </div>
    </div>
    <div class="bottom">
        <ActionButtons />
    </div>
</header>

<style>
    header {
        grid-row: 1 / 2;
        background-color: white;
        display: flex;
        flex-direction: column;
        justify-content: space-between;
        padding: 1rem 10rem;
        gap: 1rem;
    }

    .top {
        display: flex;
        justify-content: space-between;
    }

    .account {
        display: flex;
        gap: 4rem;
    }

    .bottom {
        display: flex;
        justify-content: flex-end;
    }
</style>
