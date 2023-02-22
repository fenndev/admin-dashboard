<script>
    import 'iconify-icon';
    export let username;
    export let description;
</script>

<li>
    <a href="/">
        <iconify-icon icon="mdi:account-circle" width="32" height="32" title={username} />
        <div>
            <h3>@{username}</h3>
            <p>{description}</p>
        </div>
    </a>
</li>

<style>
    li {
        list-style: none;
        width: 100%;
        text-align: center;
    }
    a {
        color: black;
        text-decoration: none;
    }
</style>
