<script>
    let { text, href, className = "bg-pink rounded-full pl-5 pr-5 h-10 w-fit"} = $props();
</script>

<button class={className}>
    <a {href}>{text}</a>
</button>