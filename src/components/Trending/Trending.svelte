<script>
    import TrendingCard from './TrendingCard.svelte';
</script>

<section>
    <h2>Trending</h2>
    <TrendingCard username={'tegan'} description={'World Peace Builder'} />
    <TrendingCard username={'morgan'} description={'Super Cool Project'} />
    <TrendingCard username={'kendall'} description={'Life Changing App'} />
    <TrendingCard username={'alex'} description={'Traffic Eraser'} />
</section>

<style>
    section {
        display: flex;
        flex-direction: column;
        justify-content: space-evenly;
        background-color: white;
        align-items: center;
        border-radius: 1rem;
    }
</style>
