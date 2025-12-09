<script>
  // Song Showcase
  const songs = [
    {
      title: "MEMORY",
      artist: "@Jace00",
      plays: "208K",
      likes: "6.0K",
      image: "https://images.unsplash.com/photo-1514525253440-b393452e8d26?q=80&w=1000&auto=format&fit=crop"
    },
    {
      title: "Stuck In My Head",
      artist: "@Kestobedo",
      plays: "46K",
      likes: "942",
      image: "https://images.unsplash.com/photo-1493225255756-d9584f8606e9?q=80&w=1000&auto=format&fit=crop"
    },
    {
      title: "goth girl knife fight.",
      artist: "@astronaut",
      plays: "38K",
      likes: "1.1K",
      image: "https://images.unsplash.com/photo-1534528741775-53994a69daeb?q=80&w=1000&auto=format&fit=crop"
    },
    {
      title: "Lo-Fi Rocks",
      artist: "@Stray Cat/Game Dev",
      plays: "38K",
      likes: "534",
      image: "https://images.unsplash.com/photo-1470225620780-dba8ba36b745?q=80&w=1000&auto=format&fit=crop"
    },
    {
      title: "I am in - I am out EDM",
      artist: "@ELIM4U",
      plays: "49K",
      likes: "981",
      image: "https://images.unsplash.com/photo-1511671782779-c97d3d27a1d4?q=80&w=1000&auto=format&fit=crop"
    }
  ];
</script>

<section class="bg-[#0a0a0a] py-24 text-white">
  <div class="container mx-auto px-6 max-w-7xl">
    <div class="mb-16 text-center">
      <h2 class="mb-6 text-4xl font-bold md:text-6xl tracking-tight leading-[1.1]">Mind blowing<br />song quality</h2>
      <p class="mx-auto max-w-3xl text-lg text-gray-400 leading-relaxed">
        Whether you have a melody in your head, lyrics you've written, or just a feeling<br class="hidden md:block"/> you want to hear—Suno makes high-quality music creation accessible to all
      </p>
    </div>

    <div class="grid grid-cols-1 gap-6 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-5">
      {#each songs as song}
        <div class="group relative aspect-[3/4] overflow-hidden rounded-xl bg-[#121212] cursor-pointer border border-white/5 hover:border-white/10 transition-all duration-300">
          <img src={song.image} alt={song.title} class="h-full w-full object-cover transition-transform duration-700 group-hover:scale-110 opacity-80 group-hover:opacity-100" />
          
          <!-- Top Left Play Icon -->
          <div class="absolute left-3 top-3 opacity-0 group-hover:opacity-100 transition-opacity duration-300">
             <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="white" stroke="currentColor" stroke-width="0" stroke-linecap="round" stroke-linejoin="round"><polygon points="5 3 19 12 5 21 5 3"></polygon></svg>
          </div>

          <!-- Bottom Gradient Overlay -->
          <div class="absolute bottom-0 left-0 right-0 bg-gradient-to-t from-black via-black/80 to-transparent p-4 pt-20">
            <h3 class="font-bold leading-tight text-white mb-1">{song.title}</h3>
            <div class="flex items-center gap-2 text-xs text-gray-300 mb-3">
              <div class="h-4 w-4 rounded-full bg-gray-600 overflow-hidden">
                  <img src={song.image} class="w-full h-full object-cover" />
              </div>
              <span class="font-medium truncate">{song.artist}</span>
            </div>
            
            <div class="flex items-center gap-4 text-[10px] font-medium text-gray-400 uppercase tracking-wide">
              <div class="flex items-center gap-1.5">
                <svg xmlns="http://www.w3.org/2000/svg" width="10" height="10" viewBox="0 0 24 24" fill="currentColor" stroke="none"><polygon points="5 3 19 12 5 21 5 3"></polygon></svg>
                {song.plays}
              </div>
              <div class="flex items-center gap-1.5">
                <svg xmlns="http://www.w3.org/2000/svg" width="10" height="10" viewBox="0 0 24 24" fill="currentColor" stroke="none"><path d="M12 21.35l-1.45-1.32C5.4 15.36 2 12.28 2 8.5 2 5.42 4.42 3 7.5 3c1.74 0 3.41.81 4.5 2.09C13.09 3.81 14.76 3 16.5 3 19.58 3 22 5.42 22 8.5c0 3.78-3.4 6.86-8.55 11.54L12 21.35z"/></svg>
                {song.likes}
              </div>
            </div>
          </div>
        </div>
      {/each}
    </div>
  </div>
</section>
