<script lang="ts">
	import Footer from '../../../components/viewOne/StaticDir/Footer.svelte';
	import Hero from '../../../components/viewOne/StaticDir/Hero.svelte';

	let { children } = $props();
</script>
<Hero />
{@render children()}
<Footer />
