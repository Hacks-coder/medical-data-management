<script>
    let { text, className = "font-basic text-pink text-2xl @md:text-4xl" } = $props()
</script>

<p class={className}>{text}</p>