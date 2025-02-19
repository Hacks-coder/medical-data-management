<script>
	import Small from "../Texts/Small.svelte";

    const footer = [
        {href: "/home", child: "Home"},
        {href: "/home", child: "Home"},
        {href: "/home", child: "Home"},
        {href: "/home", child: "Home"}
    ]
</script>

<footer class="text-center mt-20">
    <div class="flex justify-between">
        <div>logo</div>
        <div class="space-x-3">
            {#each footer as {href, child}}
                <a {href}>{child}</a>
            {/each}
        </div>
    </div>
    <hr>
    <Small text = "&copy Copyrights 2025. All Right Reserved" />
</footer>