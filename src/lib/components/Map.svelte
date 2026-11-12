<script>
    let {
        source,
        title = "just a average map",
        width = 600,
        height = 450,
        style = "border: 0;",
        allowFullscreen = false,
        loading = "lazy",
        referrerpolicy = "strict-origin-when-cross-origin"
    } = $props();
</script>


<iframe 
    title={title}
    src={source}
    width={width}
    height={height}
    style={style}
    allowfullscreen={allowFullscreen}
    loading={loading}
    referrerpolicy={referrerpolicy}
></iframe>
