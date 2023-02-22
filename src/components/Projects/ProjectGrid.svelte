<script>
    import ProjectCard from './ProjectCard.svelte';

    const content =
        'Quisque iaculis dui eu arcu lacinia, mattis rhoncus justo vulputate. Vestibulum molestie, sem ac porttitor fringilla, orci nulla molestie turpis, vitae consequat lorem elit et nisi. Ut commodo nisl vel interdum ultricies. Nunc dictum facilisis metus, ut lacinia diam faucibus a. Nullam dapibus ex felis, id scelerisque nisi sodales finibus. Nam augue sapien, iaculis at nisi sit amet, porta auctor massa. Mauris et mi vel justo vehicula congue id interdum est.';
    const title = 'Lorem Ipsum';
</script>

<div class="project-grid">
    <ProjectCard {title} {content} />
    <ProjectCard {title} {content} />
</div>

<style>
    .project-grid {
        display: grid;
        grid-template: repeat(3, minmax(0, 1fr)) / repeat(2, minmax(0, 1fr));
        gap: 2rem;
    }
</style>
