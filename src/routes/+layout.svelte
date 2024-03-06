<script>
    import "../app.css";
    const routes = [
        { href: "qr-component", text: "QR Component" },
        { href: "notification", text: "Notification Page" },
        { href: "landing", text: "Landing Page" },
        { href: "expandable", text: "Expand Able Divs" },
    ];
</script>

<div class="flex gap-3 place-content-center mt-5 mb-20">
    {#each routes as { href, text }, index}
        <a {href} class="hover:underline">{text}</a>
        {#if routes.length - 1 != index}
            |
        {/if}
    {/each}
</div>
<slot />
