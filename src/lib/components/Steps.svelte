<script lang="ts">
  const steps = [
    {
      num: "01",
      title: "Site assessment",
      desc: "Our team evaluates your runway dimensions, aircraft specifications, and regulatory requirements.",
      img: "https://images.unsplash.com/photo-1569629743817-70d8db6c323b?q=80&w=2070&auto=format&fit=crop"
    },
    {
      num: "02",
      title: "System design",
      desc: "We create a complete proposal with technical specifications and regulatory compliance documentation.",
      img: "https://images.unsplash.com/photo-1454165804606-c3d57bc86b40?q=80&w=2070&auto=format&fit=crop"
    },
    {
      num: "03",
      title: "Approval & manufacturing",
      desc: "We guide you through national approval processes while manufacturing your custom EMAS system.",
      img: "https://images.unsplash.com/photo-1581094794329-cd8119608f84?q=80&w=2070&auto=format&fit=crop"
    },
    {
      num: "04",
      title: "Installation & support",
      desc: "Professional installation with minimal runway downtime, followed by long-term maintenance and support.",
      img: "https://images.unsplash.com/photo-1583094642991-87b5c780c7e2?q=80&w=1973&auto=format&fit=crop"
    }
  ];
</script>

<section class="bg-white py-24 px-6" id="about">
  <div class="max-w-[1200px] mx-auto">
    <h2 class="text-[40px] leading-tight font-light text-gray-900 mb-16 max-w-[600px]">
      Get EMAS in four proven steps. With 20+ years of experience.
    </h2>

    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8 mb-16">
      {#each steps as step}
        <div class="flex flex-col">
          <div class="bg-black text-white text-xs font-bold w-8 h-8 flex items-center justify-center rounded mb-6">
            {step.num}
          </div>
          <h3 class="text-xl font-normal mb-2">{step.title}</h3>
          <p class="text-gray-500 text-sm leading-relaxed mb-6 min-h-[80px]">{step.desc}</p>
          <div class="rounded-xl overflow-hidden h-[200px] bg-gray-100">
            <img src={step.img} alt={step.title} class="w-full h-full object-cover grayscale hover:grayscale-0 transition-all duration-500" />
          </div>
        </div>
      {/each}
    </div>

    <div class="bg-[#f9f9f7] rounded-2xl p-12 flex flex-col md:flex-row items-center justify-between gap-8">
      <div>
        <h3 class="text-2xl font-light mb-2">Need more information?</h3>
        <p class="text-gray-500 text-sm">Learn more about our installation process and technical capabilities.</p>
      </div>
      <div class="flex gap-4">
        <button class="px-6 py-3 bg-white border border-gray-200 hover:bg-gray-50 rounded-lg text-sm font-medium transition-colors">
          Installation process
        </button>
        <button class="px-6 py-3 bg-primary-600 hover:bg-primary-700 text-white rounded-lg text-sm font-medium transition-colors flex items-center gap-2">
          <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M21 15v4a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2v-4"/><polyline points="7 10 12 15 17 10"/><line x1="12" y1="15" x2="12" y2="3"/></svg>
          Download brochure
        </button>
      </div>
    </div>
  </div>
</section>
