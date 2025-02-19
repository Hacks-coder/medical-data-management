<script>
	import ServicesCard from "../Cards/ServicesCard.svelte";
	import Title from "../Texts/Title.svelte";

    const services = [
        {
            title: "Patent Dashboard",
            description: "Manage your healthcare effortlessly with the Patient Dashboard. Schedule appointments, access medical records, track prescriptions, and view billing details in one place. Stay updated on health insights, communicate with doctors, and manage payments securely. Your health, simplified.",
            svg1: "nurse.png",
            svg2: "/img.png"
        },
        {
            title: "Patent Dashboard",
            description: "Manage your healthcare effortlessly with the Patient Dashboard. Schedule appointments, access medical records, track prescriptions, and view billing details in one place. Stay updated on health insights, communicate with doctors, and manage payments securely. Your health, simplified.",
            svg1: "nurse.png",
            svg2: "/img.png"
        },
        {
            title: "Patent Dashboard",
            description: "Manage your healthcare effortlessly with the Patient Dashboard. Schedule appointments, access medical records, track prescriptions, and view billing details in one place. Stay updated on health insights, communicate with doctors, and manage payments securely. Your health, simplified.",
            svg1: "nurse.png",
            svg2: "/img.png"
        },
        {
            title: "Patent Dashboard",
            description: "Manage your healthcare effortlessly with the Patient Dashboard. Schedule appointments, access medical records, track prescriptions, and view billing details in one place. Stay updated on health insights, communicate with doctors, and manage payments securely. Your health, simplified.",
            svg1: "nurse.png",
            svg2: "/img.png"
        },
    ]

</script>

<section class="@container text-center">
    <div>
        <Title text = "Our Services" />
        {#each services as {title, description, svg1, svg2}}
            <ServicesCard {title} {description} {svg1} {svg2} />
        {/each}
    </div>
</section>