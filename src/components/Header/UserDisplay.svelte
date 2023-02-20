<script>
    import 'iconify-icon';
</script>

<div>
    <a href="/">
        <iconify-icon icon="mdi:bell" width="24" height="24" title="Notifications" />
    </a>
    <a href="/" class="account-info">
        <iconify-icon icon="mdi:account-circle" width="72" height="72" title="Account" />
    </a>
</div>

<style>
    div {
        display: flex;
        align-items: center;
        justify-content: center;
        gap: 2rem;
    }

    a {
        text-decoration: none;
        color: black;
    }

    .account-info {
        display: block;
        text-align: center;
    }
</style>
