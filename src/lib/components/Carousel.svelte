<script lang="ts">
  const installations = [
    {
      img: "https://images.unsplash.com/photo-1464037866556-6812c9d1c72e?q=80&w=2070&auto=format&fit=crop",
      name: "Haneda Airport",
      location: "Tokyo, Japan"
    },
    {
      img: "https://images.unsplash.com/photo-1583094642991-87b5c780c7e2?q=80&w=2070&auto=format&fit=crop",
      name: "Northolt",
      location: "London, UK"
    },
    {
      img: "https://images.unsplash.com/photo-1540962351504-03099e0a754b?q=80&w=2071&auto=format&fit=crop",
      name: "Roland Garros",
      location: "Réunion, France"
    }
  ];
</script>

<section class="bg-white pb-24 overflow-hidden" id="installations">
  <div class="flex gap-4 overflow-x-auto px-6 pb-8 snap-x">
    {#each installations as installation}
      <div class="min-w-[80vw] md:min-w-[60vw] lg:min-w-[45vw] h-[400px] snap-center first:pl-0">
        <img src={installation.img} alt={installation.name} class="w-full h-full object-cover rounded-lg" />
      </div>
    {/each}
  </div>
  
  <div class="text-center mt-4">
    <p class="text-gray-500 text-sm mb-4">Major installations <span class="text-gray-400">100+ airports worldwide</span></p>
    <div class="flex justify-center gap-2">
      <div class="w-1.5 h-1.5 rounded-full bg-gray-800"></div>
      <div class="w-1.5 h-1.5 rounded-full bg-gray-300"></div>
      <div class="w-1.5 h-1.5 rounded-full bg-gray-300"></div>
    </div>
  </div>
</section>
