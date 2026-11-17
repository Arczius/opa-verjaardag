<script>
    let {
        source,
        title = "Just an average map",
        aspectRatio = "4 / 3",
        style = "border: 0;",
        allowFullscreen = false,
        loading = "lazy",
        referrerpolicy = "strict-origin-when-cross-origin"
    } = $props();
</script>

<div class="w-full overflow-hidden" style:aspect-ratio={aspectRatio}>
    <iframe
        title={title}
        src={source}
        class="w-full h-full"
        style={style}
        allowfullscreen={allowFullscreen}
        loading={loading}
        referrerpolicy={referrerpolicy}
    ></iframe>
</div>
