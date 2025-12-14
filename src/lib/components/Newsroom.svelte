<script>
    const news = [
        {
            tag: "News",
            source: "BMJ",
            title: "Evidentia launches clinical evidence platform for NHS hospital doctors",
            date: "January 15, 2024"
        },
        {
            tag: "Research",
            source: "The Lancet Digital Health",
            title: "New platform promises defensible clinical decisions through cited evidence aggregation",
            date: "January 10, 2024"
        },
        {
            tag: "News",
            source: "NHS Digital",
            title: "Evidentia partners with NHS trusts to improve evidence-based medicine",
            date: "January 5, 2024"
        }
    ];
</script>

<section class="py-24 px-6 max-w-7xl mx-auto border-t border-gray-100">
    <div class="flex justify-between items-end mb-12">
        <div>
            <h2 class="text-4xl md:text-5xl font-serif mb-8">Newsroom</h2>
            <div class="flex gap-4">
                <button class="w-12 h-12 rounded-full border border-gray-300 flex items-center justify-center hover:bg-gray-50 transition-colors">
                    <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="m15 18-6-6 6-6"/></svg>
                </button>
                <button class="w-12 h-12 rounded-full border border-gray-300 flex items-center justify-center hover:bg-gray-50 transition-colors">
                    <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="m9 18 6-6-6-6"/></svg>
                </button>
            </div>
        </div>
        <a href="#" class="hidden md:inline-flex items-center gap-2 font-medium hover:gap-3 transition-all mb-2">
            View all
            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M5 12h14"/><path d="m12 5 7 7-7 7"/></svg>
        </a>
    </div>

    <div class="grid md:grid-cols-3 gap-8">
        {#each news as item}
            <div class="group cursor-pointer">
                <div class="flex items-center gap-3 mb-4">
                    <span class="bg-blue-100 text-blue-800 text-xs font-semibold px-2 py-1 rounded">{item.tag}</span>
                    <span class="text-xs font-medium text-gray-500 uppercase tracking-wide">{item.source}</span>
                </div>
                <h3 class="text-xl font-medium mb-4 group-hover:text-blue-600 transition-colors line-clamp-3">
                    {item.title}
                </h3>
                <p class="text-xs text-gray-400 mb-8">{item.date}</p>
                <span class="text-sm font-medium inline-flex items-center gap-2 group-hover:gap-3 transition-all">
                    Read more
                    <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M5 12h14"/><path d="m12 5 7 7-7 7"/></svg>
                </span>
            </div>
        {/each}
    </div>
    
    <!-- Progress bar -->
    <div class="mt-12 w-full h-1 bg-gray-100 rounded-full overflow-hidden">
        <div class="w-1/3 h-full bg-fabric-dark rounded-full"></div>
    </div>
</section>
