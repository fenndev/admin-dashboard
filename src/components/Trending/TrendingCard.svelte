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
