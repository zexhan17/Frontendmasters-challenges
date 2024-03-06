<script>
    // @ts-nocheck
    export let color;
    export let text;
    export let grow = false;
</script>

<!-- svelte-ignore a11y-no-static-element-interactions -->
<div
    on:mouseenter={() => (grow = true)}
    on:mouseleave={() => (grow = false)}
    class="cursor-pointer group w-24 h-full transition-all duration-1000 {color} {grow
        ? 'grow'
        : ''} grid place-content-center"
>
    <span class="group-hover:rotate-180 transition-all duration-1000">
        {text}
    </span>
</div>
