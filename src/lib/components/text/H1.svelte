<script>
let {
    children
} = $props();
</script>

<h1 class="text-8xl text-blue-500 font-display first-letter:uppercase">
{@render children?.()}
</h1>
