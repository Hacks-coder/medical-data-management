<script>
    let { text, href, className = " text-white  font-bold bg-gradient-to-r from-[#5963FF] to-[#C837AB] rounded-full pl-5 pr-5 h-10 w-fit"} = $props();
</script>

<button class={className}>
    <a {href}>{text}</a>
</button>