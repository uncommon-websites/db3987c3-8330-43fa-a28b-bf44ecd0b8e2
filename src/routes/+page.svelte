<script lang="ts">
	import Navbar from "$lib/components/Navbar.svelte";
	import Hero from "$lib/components/Hero.svelte";
	import Partners from "$lib/components/Partners.svelte";
	import ValueProp from "$lib/components/ValueProp.svelte";
	import Platform from "$lib/components/Platform.svelte";
	import AISection from "$lib/components/AISection.svelte";
	import SplitSection from "$lib/components/SplitSection.svelte";
	import CaseStudies from "$lib/components/CaseStudies.svelte";
	import AboutAndInvestors from "$lib/components/AboutAndInvestors.svelte";
	import Newsroom from "$lib/components/Newsroom.svelte";
	import Footer from "$lib/components/Footer.svelte";
</script>

<div class="bg-white min-h-screen">
	<Navbar />
	
	<main>
		<Hero />
		<Partners />
		<ValueProp />
		<Platform />
		<AISection />
		
		<section class="py-24 px-6 max-w-7xl mx-auto space-y-32">
			<h2 class="text-4xl md:text-5xl font-serif max-w-3xl leading-tight">
				Built for NHS hospital doctors who need defensible clinical evidence
			</h2>
			<SplitSection type="clinicians" />
			<SplitSection type="consumers" />
		</section>

		<CaseStudies />
		<AboutAndInvestors />
		<Newsroom />
	</main>

	<Footer />
</div>

