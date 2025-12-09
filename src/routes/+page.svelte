<script>
  import Navbar from "$lib/components/Navbar.svelte";
  import Hero from "$lib/components/Hero.svelte";
  import SongShowcase from "$lib/components/SongShowcase.svelte";
  import Features from "$lib/components/Features.svelte";
  import Pricing from "$lib/components/Pricing.svelte";
  import AppRating from "$lib/components/AppRating.svelte";
  import Inspiration from "$lib/components/Inspiration.svelte";
  import Footer from "$lib/components/Footer.svelte";
</script>

<div class="min-h-screen bg-black text-white font-sans selection:bg-pink-500 selection:text-white">
  <Navbar />
  <main>
    <Hero />
    <SongShowcase />
    <Features />
    <Pricing />
    <AppRating />
    <Inspiration />
  </main>
  <Footer />
</div>


