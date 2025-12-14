<section class="py-24 bg-gray-50/50">
    <div class="max-w-7xl mx-auto px-6 grid md:grid-cols-2 gap-16 items-center">
        <div>
            <span class="inline-block bg-fabric-blue text-fabric-accent text-xs font-semibold px-3 py-1 rounded-full mb-6">Evidence Aggregation</span>
            <h2 class="text-4xl md:text-5xl font-serif mb-6">Conservative medical validation you can trust</h2>
            <p class="text-gray-600 mb-8 leading-relaxed">
                Evidentia combines comprehensive evidence aggregation with rigorous medical validation. Every recommendation is backed by cited, peer-reviewed sources and validated against established clinical guidelines.
            </p>
            
            <div class="flex flex-wrap gap-3 mb-8">
                <span class="bg-fabric-accent text-white px-5 py-2 rounded-full text-sm font-medium">Peer-Reviewed</span>
                <span class="bg-fabric-accent text-white px-5 py-2 rounded-full text-sm font-medium">Cited Sources</span>
                <span class="bg-fabric-accent text-white px-5 py-2 rounded-full text-sm font-medium">Defensible</span>
            </div>

            <a href="#" class="inline-flex items-center gap-2 font-medium hover:gap-3 transition-all">
                Learn About Our Methodology
                <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M5 12h14"/><path d="m12 5 7 7-7 7"/></svg>
            </a>
        </div>

        <div class="relative flex justify-center items-center">
            <!-- Concentric Circles Diagram -->
            <div class="relative w-[400px] h-[400px] flex items-center justify-center">
                <!-- Outer Circle -->
                <div class="absolute inset-0 rounded-full bg-fabric-blue blur-xl"></div>
                <div class="absolute inset-4 rounded-full border border-fabric-accent/30 bg-fabric-blue"></div>
                
                <!-- Middle Circle -->
                <div class="absolute inset-[60px] rounded-full border border-fabric-accent/40 bg-white/50"></div>
                
                <!-- Inner Circle -->
                <div class="absolute inset-[110px] rounded-full border border-fabric-accent bg-fabric-accent/10 flex items-center justify-center text-center p-4">
                    <span class="font-serif font-bold text-sm leading-tight">Medical<br>Validation<br>Engine</span>
                </div>

                <!-- Labels on paths -->
                <svg class="absolute inset-0 w-full h-full" viewBox="0 0 400 400">
                    <path id="curve1" d="M 60,200 A 140,140 0 0,1 340,200" fill="none" />
                    <text class="text-xs font-medium uppercase tracking-wider fill-gray-700">
                        <textPath href="#curve1" startOffset="50%" text-anchor="middle">Peer-Reviewed Evidence</textPath>
                    </text>
                    
                    <path id="curve2" d="M 110,200 A 90,90 0 0,1 290,200" fill="none" />
                    <text class="text-[10px] font-medium uppercase tracking-wider fill-gray-600">
                        <textPath href="#curve2" startOffset="50%" text-anchor="middle">Clinical Guidelines</textPath>
                    </text>
                </svg>
            </div>
        </div>
    </div>
</section>
