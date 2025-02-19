<script>
	import Basic from "../Texts/Basic.svelte";
	import Small from "../Texts/Small.svelte";

    let {title, description, svg1, svg2 } =  $props();
</script>

<section>
    <div class="grid gap-20 place-items-center @3xl:grid-cols-2">
        <div>
            <Basic text = {title} />
            <Small text = {description} />
            <div style={`background-image: url(${svg1})`} class="bg-cover bg-center size-50"></div>
        </div>
        <div style={`background-image: url(${svg2})`} class="bg-cover bg-center size-72"></div>
    </div>
</section>