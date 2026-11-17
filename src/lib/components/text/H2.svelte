<script>
let {
    children
} = $props();
</script>

<h2 class="font-bold text-2xl first-letter:uppercase">
{@render children?.()}
</h2>
