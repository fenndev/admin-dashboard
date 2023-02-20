<script>
    import AnnouncementsCard from './AnnouncementsCard.svelte';
    const title = 'Lorem Ipsum';
    const content =
        'Quisque iaculis dui eu arcu lacinia, mattis rhoncus justo vulputate. Vestibulum molestie, sem ac porttitor fringilla, orci nulla molestie turpis, vitae consequat lorem elit et nisi. Ut commodo nisl vel interdum ultricies. Nunc dictum facilisis metus, ut lacinia diam faucibus a. Nullam dapibus ex felis, id scelerisque nisi sodales finibus. Nam augue sapien, iaculis at nisi sit amet, porta auctor massa. Mauris et mi vel justo vehicula congue id interdum est.';
</script>

<section>
    <h2>Announcements</h2>
    <ul>
        <AnnouncementsCard {title} {content} />
        <AnnouncementsCard {title} {content} />
        <AnnouncementsCard {title} {content} />
    </ul>
</section>

<style>
    section {
        border-radius: 1rem;
        background-color: white;
        padding: 0 4rem;
    }
    h2 {
        font-size: 2.4rem;
    }

    ul {
        padding: 0;
        margin: 0;
        list-style: none;
    }
</style>
