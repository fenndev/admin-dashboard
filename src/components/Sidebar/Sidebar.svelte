<script>
    import 'iconify-icon';
</script>

<nav>
    <ul role="navigation">
        <li>
            <a href="/">
                <iconify-icon icon="mdi:home" width="24" height="24" title="Home" />
                <span>Home</span>
            </a>
        </li>
        <li>
            <a href="/">
                <iconify-icon icon="mdi:account" width="24" height="24" title="Account" />
                <span>Account</span>
            </a>
        </li>
        <li>
            <a href="/">
                <iconify-icon icon="mdi:message-badge" width="24" height="24" title="Messages" />
                <span>Messages</span>
            </a>
        </li>
        <li>
            <a href="/">
                <iconify-icon icon="mdi:history" width="24" height="24" title="History" />
                <span>History</span>
            </a>
        </li>
        <li>
            <a href="/">
                <iconify-icon icon="mdi:cog" width="24" height="24" title="Settings" />
                <span>Settings</span>
            </a>
        </li>
        <li>
            <a href="/">
                <iconify-icon icon="mdi:tooltip-question" width="24" height="24" title="Support" />
                <span>Support</span>
            </a>
        </li>
        <li>
            <a href="/">
                <iconify-icon icon="mdi:shield-account" width="24" height="24" title="Privacy" />
                <span>Privacy</span>
            </a>
        </li>
    </ul>
</nav>

<style>
    nav {
        grid-column: 1 / 2;
        grid-row: 1 / 3;
        padding: 4rem 2rem 20rem 2rem;
        background-color: slategray;
    }

    ul {
        height: inherit;
        display: flex;
        flex-direction: column;
        justify-content: space-between;
        list-style-type: none;
        margin: 0;
        padding: 0;
        gap: 4rem;
    }

    li {
        text-decoration: none;
        color: white;
    }

    a {
        color: white;
        text-decoration: none;
        display: flex;
        align-items: center;
        gap: 1.5rem;
    }

    a:focus,
    a:hover {
        background-color: #4a4a4a;
    }

    span {
        font-size: 1.6rem;
    }
</style>
