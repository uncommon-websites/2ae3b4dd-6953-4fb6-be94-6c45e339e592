<script lang="ts">
</script>

<section class="bg-[#f0efeb] py-24 px-6">
  <div class="max-w-[1200px] mx-auto">
    <div class="grid grid-cols-1 md:grid-cols-2 gap-12 mb-24">
      <div>
        <h2 class="text-[40px] font-light text-gray-900 leading-tight mb-6">
          A sustainable future<br>starts with<br>greenEMAS.
        </h2>
        <p class="text-gray-500 text-sm max-w-[300px]">
          greenEMAS is engineered for environmental responsibility. Made from 100% recycled glass and produced with renewable energy, it delivers runway safety while minimizing environmental impact.
        </p>
      </div>

      <div class="grid grid-cols-2 gap-8">
        <div class="bg-white/50 p-8 rounded-xl border border-white/60">
          <div class="text-[40px] font-light mb-2">100<span class="text-lg ml-1">%</span></div>
          <p class="text-gray-500 text-xs uppercase tracking-wide mb-4">recycled glass</p>
          <p class="text-gray-400 text-[10px] leading-relaxed">
            greenEMAS is made entirely from recycled glass (silica foam).
          </p>
        </div>
        <div class="bg-white/50 p-8 rounded-xl border border-white/60">
          <div class="text-[40px] font-light mb-2">0<span class="text-lg ml-1">ha</span></div>
          <p class="text-gray-500 text-xs uppercase tracking-wide mb-4">land reclamation</p>
          <p class="text-gray-400 text-[10px] leading-relaxed">
            Reduces need to reclaim land for runway expansion.
          </p>
        </div>
      </div>
    </div>

    <!-- Environmental Image -->
    <div class="w-full h-[500px] rounded-2xl overflow-hidden mb-8 relative">
      <img 
        src="https://images.unsplash.com/photo-1532996122724-e3c354a0b15b?q=80&w=2070&auto=format&fit=crop" 
        alt="Sustainable materials" 
        class="w-full h-full object-cover"
      />
    </div>

    <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
      <!-- Card 1 -->
      <div class="bg-[#fdfbf7] p-8 rounded-2xl min-h-[300px] flex flex-col justify-end">
        <h3 class="text-xl font-normal mb-2">Renewable energy<br>production</h3>
        <p class="text-gray-500 text-xs leading-relaxed mb-4">
          greenEMAS is produced using renewable energy sources, further reducing environmental footprint.
        </p>
        <a href="#" class="text-xs font-medium flex items-center gap-1">Details -></a>
      </div>

      <!-- Card 2 (Primary) -->
      <div class="bg-primary-700 p-8 rounded-2xl min-h-[300px] flex flex-col justify-between text-white relative overflow-hidden group">
         <img 
            src="https://images.unsplash.com/photo-1569629743817-70d8db6c323b?q=80&w=2021&auto=format&fit=crop" 
            class="absolute inset-0 w-full h-full object-cover opacity-30 mix-blend-overlay"
            alt="Long-lasting materials"
         />
         <div class="relative z-10 h-full flex flex-col justify-end">
            <h3 class="text-xl font-normal mb-2">Long-lasting materials</h3>
            <p class="text-white/80 text-xs leading-relaxed mb-4">
            Designed for durability with comprehensive lifecycle support and fast repairs with short lead times.
            </p>
            <a href="#" class="text-xs font-medium flex items-center gap-1">Learn more -></a>
        </div>
      </div>

      <!-- Card 3 (Green) -->
      <div class="bg-green-600 p-8 rounded-2xl min-h-[300px] flex flex-col justify-between relative overflow-hidden">
         <img 
            src="https://images.unsplash.com/photo-1532996122724-e3c354a0b15b?q=80&w=2072&auto=format&fit=crop" 
            class="absolute inset-0 w-full h-full object-cover opacity-20 mix-blend-overlay"
            alt="Environmental impact"
         />
         <div class="relative z-10 h-full flex flex-col justify-end">
            <h3 class="text-xl font-normal mb-2 text-white">Minimal environmental impact</h3>
            <p class="text-white/80 text-xs leading-relaxed mb-4">
            Reduces environmental impact compared to traditional runway expansion and land acquisition.
            </p>
            <a href="#" class="text-xs font-medium text-white flex items-center gap-1">Details -></a>
        </div>
      </div>
    </div>
  </div>
</section>
