<script>

	import Small from "../Texts/Small.svelte";
    const photo = '/photo.png'
</script>
<section class="@container mt-10">
    <div class="grid place-items-center gap-10 @3xl:grid-cols-2">
        <div class="text-center flex flex-col items-center gap-5    ">
            <p class="border-4 border-pink rounded-full pl-5 pr-5 text-md w-fit @md:text-2xl @xl:text-3xl">What’s New?</p>
            <p class="text-3xl font-krona font-bold">Mental Health is Wealth</p>
            <div class="flex gap-5">
                <div class="w-15 h-15 rounded-full bg-pink"></div>
                <Small text = "To live your life to the fullest we have provide a means where you can track your medical report." />
            </div>
        </div>
        <div style={`background-image: url(${photo})`} class="size-72 bg-cover bg-center"></div>
    </div>
</section>