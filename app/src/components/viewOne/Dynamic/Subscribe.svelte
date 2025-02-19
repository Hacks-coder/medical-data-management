<script>
	import Gradient from "../Buttons/Gradient.svelte";


	import Small from "../Texts/Small.svelte";

</script>
<section class="flex justify-center">
    <div class="space-y-5">
        <p>Subscribe to our monthly newsletter</p>
        <Small text = "Let us make you dream business come true" />
        <div class="bg-white shadow-md shadow-black rounded-full gap-2 p-2 w-fit h-fit">
            <input type="email" placeholder="Your email address gradient"><Gradient />
        </div>
    </div>
</section>