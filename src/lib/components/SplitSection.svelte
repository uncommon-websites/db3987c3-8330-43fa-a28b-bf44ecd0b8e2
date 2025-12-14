<script lang="ts">
    export let type: "clinicians" | "consumers" = "clinicians";
    
    const content = {
        clinicians: {
            title: "For hospital registrars...",
            items: [
                { title: "Make defensible decisions", desc: "Every recommendation backed by cited, peer-reviewed evidence you can trust." },
                { title: "Save time searching", desc: "Stop wasting hours on unreliable sources. Get validated evidence instantly." },
                { title: "Build peer trust", desc: "Share evidence with colleagues through defensible cited sources." }
            ],
            image: "/generated/image-doctor-making-clinical-decisions-with-co-1765724315946-3.webp",
            overlay: true
        },
        consumers: {
            title: "For teaching rounds...",
            items: [
                { title: "Present with confidence", desc: "Cite peer-reviewed evidence during ward rounds and teaching sessions." },
                { title: "Stay current", desc: "Access the latest clinical guidelines and systematic reviews." },
                { title: "Overcome trust concerns", desc: "Conservative validation ensures recommendations align with medical consensus." }
            ],
            image: "/generated/image-confident-hospital-registrar-during-teac-1765724313326-2.webp",
            overlay: false
        }
    };

    $: data = content[type];
</script>

<div class="grid md:grid-cols-2 gap-16 items-center">
    <div class="{type === 'consumers' ? 'md:order-2' : ''}">
        <h3 class="text-2xl font-serif mb-8">{data.title}</h3>
        <ul class="space-y-8 mb-10">
            {#each data.items as item}
                <li class="flex gap-4">
                    <div class="mt-1 text-gray-400">
                        <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><polyline points="20 6 9 17 4 12"/></svg>
                    </div>
                    <div>
                        <h4 class="font-medium text-lg mb-1">{item.title}</h4>
                        <p class="text-gray-600 text-sm leading-relaxed">{item.desc}</p>
                    </div>
                </li>
            {/each}
        </ul>
        <button class="bg-fabric-accent text-white px-6 py-2.5 rounded-full text-sm font-medium hover:bg-fabric-green-dark transition-colors">
            Request Early Access
        </button>
    </div>

    <div class="relative {type === 'consumers' ? 'md:order-1' : ''}">
        <div class="relative rounded-lg overflow-hidden shadow-xl">
            <img src={data.image} alt={type} class="w-full h-[500px] object-cover" />
            
            <!-- Overlay UI Mockups -->
            {#if type === 'clinicians'}
                <div class="absolute top-1/2 left-4 right-4 transform -translate-y-1/2 bg-white rounded-lg shadow-lg p-4 max-w-xs">
                    <div class="flex items-center gap-2 mb-3 border-b border-gray-100 pb-2">
                         <div class="w-2 h-2 bg-fabric-accent rounded-full"></div>
                         <span class="text-xs font-medium">Evidence for acute MI management</span>
                    </div>
                    <div class="space-y-2">
                        <div class="bg-gray-50 p-2 rounded">
                            <p class="text-[10px] font-semibold text-gray-500 mb-1">Top Guidelines</p>
                            <div class="flex gap-2 items-center">
                                <div class="text-[8px] bg-fabric-accent text-white px-1 py-0.5 rounded font-bold">A</div>
                                <div class="h-1.5 bg-gray-200 w-20 rounded"></div>
                            </div>
                        </div>
                         <div class="bg-gray-50 p-2 rounded">
                            <p class="text-[10px] font-semibold text-gray-500 mb-1">Cited Sources</p>
                            <div class="h-1.5 bg-gray-200 w-full rounded mb-1"></div>
                            <div class="h-1.5 bg-gray-200 w-2/3 rounded"></div>
                        </div>
                        <div class="bg-fabric-accent text-white text-[10px] p-2 rounded text-center">
                            View full evidence summary
                        </div>
                    </div>
                </div>
            {:else}
                 <div class="absolute bottom-10 right-4 bg-white rounded-lg shadow-lg p-4 max-w-xs w-64">
                    <div class="space-y-3">
                        <div class="bg-fabric-blue p-3 rounded-lg rounded-tl-none text-xs">
                            Teaching Round Query
                            <br/>
                            "What's the evidence for dual antiplatelet therapy?"
                             <div class="mt-2 bg-fabric-accent text-white inline-block px-2 py-1 rounded-full text-[10px]">Search evidence</div>
                        </div>
                        <div class="bg-gray-100 p-3 rounded-lg rounded-tr-none ml-auto text-xs w-fit">
                            Evidence Level: Grade A
                            <div class="mt-2 space-y-1">
                                <div class="flex items-center gap-2 bg-white p-1 rounded border border-gray-200">
                                    <div class="w-3 h-3 bg-fabric-accent rounded-sm"></div>
                                    <span class="text-[10px]">ESC Guidelines 2023</span>
                                </div>
                                <div class="flex items-center gap-2 bg-white p-1 rounded border border-gray-200">
                                    <div class="w-3 h-3 bg-fabric-accent rounded-sm"></div>
                                    <span class="text-[10px]">Lancet Meta-analysis</span>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            {/if}
        </div>
    </div>
</div>
