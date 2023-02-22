<script>
    import ProjectGrid from './Projects/ProjectGrid.svelte';
    import Announcements from './Announcements/Announcements.svelte';
    import Trending from './Trending/Trending.svelte';
</script>

<main>
    <ProjectGrid />
    <aside>
        <Announcements />
        <Trending />
    </aside>
</main>

<style>
    main {
        grid-row: 2 / 3;
        display: flex;
        gap: 2rem;
        padding: 2rem 6rem;
    }

    aside {
        display: flex;
        flex-direction: column;
        gap: 2rem;
    }
</style>
