<script>
	import Gradient from "../Buttons/Gradient.svelte";


	import Small from "../Texts/Small.svelte";

</script>
<section class="flex justify-center mt-20">
    <div class="gap-3 flex flex-col items-center text-center">
        <p class="font-bold text-xl">Subscribe to our monthly newsletter</p>
        <Small text = "Let us make you dream business come true" />
        <div class="bg-white shadow-sm shadow-black rounded-full gap-2 p-2 w-fit h-fit space-x-5">
            <input type="email" placeholder="Your email address gradient"><Gradient text = "Send" />
        </div>
    </div>
</section>