<script>
  // Inspiration Section
  const inspirations = [
    {
      user: "@devonibiza",
      image: "https://images.unsplash.com/photo-1570295999919-56ceb5ecca61?q=80&w=1000&auto=format&fit=crop"
    },
    {
      user: "@techguyver",
      image: "https://images.unsplash.com/photo-1522075469751-3a3694c2dd77?q=80&w=1000&auto=format&fit=crop"
    },
    {
      user: "@timbaland",
      image: "https://images.unsplash.com/photo-1531427186611-ecfd6d936c79?q=80&w=1000&auto=format&fit=crop"
    },
    {
      user: "@spellspellspell",
      image: "https://images.unsplash.com/photo-1506794778202-cad84cf45f1d?q=80&w=1000&auto=format&fit=crop"
    },
    {
      user: "@nickfloats",
      image: "https://images.unsplash.com/photo-1500648767791-00dcc994a43e?q=80&w=1000&auto=format&fit=crop"
    }
  ];
</script>

<section class="bg-[#0a0a0a] py-32 text-white">
  <div class="container mx-auto px-6 text-center max-w-7xl">
    <h2 class="mb-6 text-4xl font-bold md:text-6xl tracking-tight leading-[1.1]">Explore and get<br />inspired</h2>
    <p class="mx-auto mb-20 max-w-2xl text-gray-400 text-lg">
      Join the #1 AI music generator. Create songs, remix<br class="hidden md:block" /> tracks, make beats, and share your music with<br class="hidden md:block" /> millions — free forever.
    </p>

    <div class="mb-20 grid grid-cols-2 gap-4 md:grid-cols-5">
      {#each inspirations as item}
        <div class="group relative aspect-[9/16] overflow-hidden rounded-2xl bg-[#121212] cursor-pointer">
          <img src={item.image} alt={item.user} class="h-full w-full object-cover transition-transform duration-700 group-hover:scale-110 opacity-90 group-hover:opacity-100" />
          
          <!-- Play Icon -->
          <div class="absolute left-3 top-3">
             <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="white" stroke="currentColor" stroke-width="0" stroke-linecap="round" stroke-linejoin="round"><polygon points="5 3 19 12 5 21 5 3"></polygon></svg>
          </div>

          <!-- User Overlay -->
          <div class="absolute bottom-0 left-0 w-full bg-gradient-to-t from-black/90 via-black/50 to-transparent p-4 text-left pt-12">
            <p class="text-sm font-bold text-white tracking-wide">{item.user}</p>
          </div>
        </div>
      {/each}
    </div>

    <button class="rounded-xl bg-gradient-to-r from-[#ff6b3d] to-[#ff3d71] px-10 py-4 text-lg font-bold text-white transition-opacity hover:opacity-90 shadow-lg shadow-orange-500/20">
      Sign up for free
    </button>
  </div>
</section>
