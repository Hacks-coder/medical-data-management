<script>
	import Gradient from "../Buttons/Gradient.svelte";
	import Small from "../Texts/Small.svelte";
	import Title from "../Texts/Title.svelte";

    const nurse = "/nurse.png"
</script>

<section class="@container mt-20 pr-10 pl-10">
    <div class="grid place-items-center text-center gap-10 @3xl:grid-cols-2">
        <div style={`background-image: url(${nurse})`} class="bg-cover bg-center size-72"></div>
        <div class="flex flex-col gap-5 items-center">
            <Title text = "How can we help you?" />
            <Small text = "We collaborate with world-class experts to develop human-centered tools and services that drive sustainable growth. 
                Our data-driven approach ensures that every decision is focused on enhancing your wellbeing." />
            <Gradient text = "Get Started" href = ""/>
        </div>
    </div>
</section>