<script>
    const cards = [
        {
            title: "Evidence Search",
            image: "/generated/image-medical-research-papers-and-peer-reviewe-1765724310866-1.webp",
            color: "bg-fabric-dark"
        },
        {
            title: "Citation Management",
            image: "/generated/image-nhs-hospital-doctor-in-scrubs-reviewing--1765724307733-0.webp",
            color: "bg-fabric-green"
        },
        {
            title: "Clinical Validation",
            image: "/generated/image-doctor-making-clinical-decisions-with-co-1765724315946-3.webp",
            color: "bg-fabric-blue"
        }
    ];
</script>

<section class="py-24 px-6 max-w-7xl mx-auto">
    <div class="flex flex-col md:flex-row justify-between items-end mb-12 gap-8">
        <div class="max-w-2xl">
            <h2 class="text-4xl md:text-5xl font-serif mb-6 leading-tight">
                Clinical evidence platform built for NHS hospital doctors
            </h2>
            <p class="text-gray-600 text-lg">
                Evidentia aggregates peer-reviewed evidence and provides conservative medical validation, giving you defensible clinical decisions backed by cited sources you can trust.
            </p>
        </div>
        <div class="flex gap-4">
            <button class="w-12 h-12 rounded-full border border-gray-300 flex items-center justify-center hover:bg-gray-50 transition-colors">
                <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="m15 18-6-6 6-6"/></svg>
            </button>
            <button class="w-12 h-12 rounded-full border border-gray-300 flex items-center justify-center hover:bg-gray-50 transition-colors">
                <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="m9 18 6-6-6-6"/></svg>
            </button>
        </div>
    </div>

    <div class="grid md:grid-cols-3 gap-6">
        {#each cards as card}
            <div class="group cursor-pointer overflow-hidden rounded-lg">
                <div class="relative h-64 overflow-hidden">
                    <img src={card.image} alt={card.title} class="w-full h-full object-cover transition-transform duration-500 group-hover:scale-105" />
                </div>
                <div class="{card.color === 'bg-fabric-blue' ? 'bg-blue-100 text-fabric-dark' : card.color === 'bg-fabric-green' ? 'bg-[#9BB0A5] text-white' : 'bg-[#0B1221] text-white'} p-6 h-32 flex items-end">
                    <h3 class="text-xl font-medium">{card.title}</h3>
                </div>
            </div>
        {/each}
    </div>
</section>
