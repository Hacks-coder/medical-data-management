<script>
    let { text, className = " text-white bg-pink font-bold h-10 w-80"} = $props();
</script>

<button class={className}>
    {text}
</button>