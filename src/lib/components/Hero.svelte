<script lang="ts">
</script>

<section class="pt-32 pb-16 md:pt-40 md:pb-24 px-6 max-w-7xl mx-auto grid md:grid-cols-2 gap-12 items-center">
  <div class="space-y-8">
    <h1 class="text-5xl md:text-7xl font-serif font-medium leading-[1.1]">
      Defensible clinical <br/> decisions
    </h1>
    <p class="text-lg md:text-xl text-gray-600 max-w-lg leading-relaxed">
      Evidentia delivers cited, peer-reviewed evidence aggregation and conservative medical validation—empowering NHS hospital doctors with defensible clinical decisions at the point of care.
    </p>
    <div class="flex flex-wrap gap-4">
      <button class="bg-fabric-accent text-white px-6 py-3 rounded-full font-medium hover:bg-fabric-green-dark transition-colors flex items-center gap-2">
        Request Early Access
        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M5 12h14"/><path d="m12 5 7 7-7 7"/></svg>
      </button>
      <button class="border border-gray-300 px-6 py-3 rounded-full font-medium hover:border-gray-400 transition-colors flex items-center gap-2">
        View Evidence Library
        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M5 12h14"/><path d="m12 5 7 7-7 7"/></svg>
      </button>
    </div>
  </div>

  <div class="relative">
    <!-- Background shape -->
    <div class="absolute -top-10 -right-10 w-[120%] h-[120%] bg-fabric-pink rounded-[3rem] -z-10 transform rotate-2"></div>
    
    <!-- UI Mockup -->
    <div class="relative bg-white rounded-xl shadow-xl p-6 md:p-8 border border-gray-100">
      <div class="flex items-center justify-between mb-6">
        <div>
          <h3 class="text-2xl font-serif">Clinical Evidence Search</h3>
          <div class="flex items-center gap-2 mt-2">
            <div class="w-6 h-6 rounded-full bg-fabric-accent flex items-center justify-center text-white text-xs font-bold">
                DS
            </div>
            <span class="text-sm text-gray-500">Dr. Douglas Stark</span>
          </div>
        </div>
        <div class="text-right">
            <svg width="24" height="24" viewBox="0 0 97 97" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path fill-rule="evenodd" clip-rule="evenodd" d="M96.8438 48.3333C96.8438 75.0271 75.3534 96.6667 48.8438 96.6667C25.3046 96.6667 5.72283 79.605 1.63005 57.0928C1.61771 57.0251 1.60551 56.9572 1.59346 56.8891C1.10084 54.1121 0.84375 51.2529 0.84375 48.3333C0.84375 46.0025 1.00762 43.71 1.32439 41.4671C4.31845 20.2681 20.9721 3.49883 42.0249 0.483986C42.0602 0.478911 42.0954 0.473908 42.131 0.468905C44.3246 0.159814 46.5657 0 48.8438 0C51.8142 0 54.7216 0.271706 57.5428 0.791773C79.8997 4.91296 96.8438 24.6307 96.8438 48.3333ZM84.8438 48.3333C84.8438 68.3537 68.7261 84.5833 48.8438 84.5833C33.861 84.5833 21.0159 75.3669 15.5951 62.257C17.8219 62.6361 20.1099 62.8333 22.4438 62.8333C44.9769 62.8333 63.2438 44.4396 63.2438 21.75C63.2438 19.4 63.0479 17.096 62.6714 14.8538C75.6909 20.3123 84.8438 33.2466 84.8438 48.3333ZM49.6077 12.0913C50.6673 15.1126 51.2438 18.3635 51.2438 21.75C51.2438 37.7662 38.3495 50.75 22.4438 50.75C19.0806 50.75 15.8521 50.1695 12.8517 49.1026C12.8464 48.8469 12.8438 48.5905 12.8438 48.3333C12.8438 28.3129 28.9614 12.0833 48.8438 12.0833C49.0991 12.0833 49.3538 12.086 49.6077 12.0913Z" fill="currentColor"/>
            </svg>
        </div>
      </div>

      <div class="grid grid-cols-3 gap-4">
        <div class="col-span-1 space-y-4">
            <div class="bg-gray-50 p-3 rounded-lg border border-gray-100">
                <p class="text-xs text-gray-500 mb-2">Search Query</p>
                <div class="bg-white p-2 rounded border border-gray-200">
                    <span class="text-[10px] block">Treatment guidelines for acute coronary syndrome</span>
                </div>
            </div>
             <div class="bg-gray-50 p-3 rounded-lg border border-gray-100">
                <p class="text-xs text-gray-500 mb-2">Filter by Evidence Level</p>
                <div class="space-y-1">
                    <div class="bg-fabric-accent text-white p-1.5 rounded text-[10px] font-medium">Systematic Reviews</div>
                    <div class="bg-white p-1.5 rounded border border-gray-200 text-[10px]">RCTs</div>
                    <div class="bg-white p-1.5 rounded border border-gray-200 text-[10px]">Guidelines</div>
                </div>
            </div>
        </div>
        
        <div class="col-span-2 bg-gray-50 p-4 rounded-lg border border-gray-100">
            <div class="flex justify-between items-center mb-3">
                <span class="text-xs font-semibold">Evidence Results (247 sources)</span>
            </div>
            <div class="space-y-2">
                <div class="bg-white p-3 rounded border border-gray-200 shadow-sm">
                    <div class="flex items-start gap-2 mb-2">
                        <div class="text-[8px] bg-fabric-accent text-white px-1.5 py-0.5 rounded font-bold">A</div>
                        <div class="flex-1">
                            <p class="text-[10px] font-semibold mb-1">ESC Guidelines for ACS Management</p>
                            <p class="text-[8px] text-gray-500">European Heart Journal, 2023</p>
                        </div>
                    </div>
                    <div class="flex gap-1 text-[8px]">
                        <span class="bg-green-100 text-green-700 px-1.5 py-0.5 rounded">Peer-reviewed</span>
                        <span class="bg-blue-100 text-blue-700 px-1.5 py-0.5 rounded">Guideline</span>
                    </div>
                </div>
                
                <div class="bg-white p-3 rounded border border-gray-200 shadow-sm">
                    <div class="flex items-start gap-2 mb-2">
                        <div class="text-[8px] bg-fabric-accent text-white px-1.5 py-0.5 rounded font-bold">A</div>
                        <div class="flex-1">
                            <p class="text-[10px] font-semibold mb-1">Dual Antiplatelet Therapy in ACS</p>
                            <p class="text-[8px] text-gray-500">The Lancet, 2023</p>
                        </div>
                    </div>
                    <div class="flex gap-1 text-[8px]">
                        <span class="bg-green-100 text-green-700 px-1.5 py-0.5 rounded">Meta-analysis</span>
                        <span class="bg-purple-100 text-purple-700 px-1.5 py-0.5 rounded">RCT</span>
                    </div>
                </div>

                <div class="mt-3 bg-fabric-blue p-2 rounded flex items-center gap-2">
                    <svg xmlns="http://www.w3.org/2000/svg" width="12" height="12" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M12 2v20M2 12h20"/></svg>
                    <p class="text-[10px] font-medium">All sources cited and validated</p>
                </div>
            </div>
        </div>
      </div>
    </div>
  </div>
</section>
