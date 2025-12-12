<script lang="ts">
  import TopBanner from "$lib/components/TopBanner.svelte";
  import Navbar from "$lib/components/Navbar.svelte";
  import Hero from "$lib/components/Hero.svelte";
  import Intro from "$lib/components/Intro.svelte";
  import Carousel from "$lib/components/Carousel.svelte";
  import ValueProp from "$lib/components/ValueProp.svelte";
  import ShowroomGrid from "$lib/components/ShowroomGrid.svelte";
  import LifeWithBackyard from "$lib/components/LifeWithBackyard.svelte";
  import ProductConfigurator from "$lib/components/ProductConfigurator.svelte";
  import PeekInside from "$lib/components/PeekInside.svelte";
  import Steps from "$lib/components/Steps.svelte";
  import Features from "$lib/components/Features.svelte";
  import Illustration from "$lib/components/Illustration.svelte";
  import Sustainability from "$lib/components/Sustainability.svelte";
  import Footer from "$lib/components/Footer.svelte";
</script>

<svelte:head>
  <title>Runway Safe - EMAS Runway Safety Systems | 100+ Global Installations</title>
  <meta name="description" content="Runway Safe provides proven EMAS (Engineered Material Arresting System) solutions for airports worldwide. FAA, ICAO, and EASA approved. 100+ installations across four continents. greenEMAS made from 100% recycled glass." />
</svelte:head>

<div class="font-sans antialiased text-gray-900 bg-white">
  <TopBanner />
  <Navbar />
  <main>
    <Hero />
    <Intro />
    <Carousel />
    <ValueProp />
    <ShowroomGrid />
    <LifeWithBackyard />
    <ProductConfigurator />
    <PeekInside />
    <Steps />
    <Features />
    <Illustration />
    <Sustainability />
  </main>
  <Footer />
</div>

