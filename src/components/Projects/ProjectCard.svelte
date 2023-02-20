<script>
    export let title = '';
    export let content = '';
    import 'iconify-icon';
</script>

<article>
    <h3 class="card-title">{title}</h3>
    <p class="card-content">{content}</p>
    <div class="action-icon-container">
        <button aria-label="Favorite">
            <iconify-icon icon="mdi:star-plus" width="24" height="24" title="Favorite" />
        </button>
        <button aria-label="Watch">
            <iconify-icon icon="mdi:eye-plus" width="24" height="24" title="Watch" />
        </button>
        <button aria-label="Share">
            <iconify-icon icon="mdi:share-variant" width="24" height="24" title="Share" />
        </button>
    </div>
</article>

<style>
    article {
        display: flex;
        flex-direction: column;
        background-color: white;
        gap: 2rem;
        padding: 2rem 5rem;
        border-radius: 1rem;
    }

    h3 {
        font-size: 2.4rem;
    }

    p {
        font-size: 1.6rem;
    }

    h3,
    p,
    div {
        padding: 0 2rem;
    }

    div {
        display: flex;
        align-self: flex-end;
        gap: 4rem;
    }

    button {
        background-color: transparent;
        border: none;
        cursor: pointer;
        padding: 0;
    }

    button:focus {
        outline: none;
    }
</style>
