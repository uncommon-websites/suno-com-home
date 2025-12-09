<script>
  // Hero Section
</script>

<section class="relative flex min-h-[90vh] flex-col items-center justify-center overflow-hidden bg-[#0a0a0a] px-4 pt-32 text-center text-white">
  <!-- Background Gradients -->
  <div class="absolute inset-0 z-0 pointer-events-none">
    <!-- Top Right Orange Glow -->
    <div class="absolute -top-[10%] -right-[5%] h-[600px] w-[600px] rounded-full bg-[#ea580c]/40 blur-[100px] opacity-80 mix-blend-screen"></div>
    <!-- Top Left Purple Glow -->
    <div class="absolute -top-[10%] -left-[10%] h-[600px] w-[600px] rounded-full bg-[#7e22ce]/30 blur-[100px] opacity-60 mix-blend-screen"></div>
    <!-- Center Top Warmth -->
    <div class="absolute top-0 left-1/2 -translate-x-1/2 h-[500px] w-[800px] rounded-full bg-gradient-to-b from-[#c2410c]/20 via-[#7e22ce]/10 to-transparent blur-[80px]"></div>
    
    <!-- Noise Texture Overlay (Optional, simulated with pattern) -->
    <div class="absolute inset-0 opacity-[0.03] bg-[url('https://grainy-gradients.vercel.app/noise.svg')]"></div>
  </div>

  <div class="relative z-10 mx-auto max-w-5xl mt-10">
    <h1 class="mb-8 text-5xl font-bold leading-[1.05] tracking-tighter md:text-7xl lg:text-8xl">
      Make a house song about<br />quitting your job
    </h1>
    <p class="mb-14 text-lg text-gray-300 md:text-xl max-w-2xl mx-auto leading-relaxed font-medium">
      Start with a simple prompt or dive into our pro editing<br class="hidden md:block"/> tools, your next track is just a step away.
    </p>

    <!-- Input Box -->
    <div class="relative mx-auto mb-28 w-full max-w-2xl group">
        <!-- Glow effect behind input -->
        <div class="absolute -inset-0.5 bg-gradient-to-r from-orange-500 to-purple-600 rounded-2xl opacity-30 group-hover:opacity-50 blur transition duration-500"></div>
        
        <div class="relative flex items-center gap-3 rounded-2xl border border-white/10 bg-[#18181b] p-2 pr-2 shadow-2xl">
            <!-- Plus Button -->
            <button class="flex h-12 w-12 items-center justify-center rounded-xl text-gray-400 hover:bg-white/10 hover:text-white transition-colors">
                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M5 12h14"/><path d="M12 5v14"/></svg>
            </button>
            
            <!-- Input -->
            <input 
                type="text" 
                placeholder="Chat to make music" 
                class="flex-1 bg-transparent text-lg text-white placeholder-gray-500 outline-none h-12"
            />
            
            <!-- Right Actions -->
            <div class="flex items-center gap-3">
                <!-- Advanced Toggle -->
                <button class="hidden sm:flex items-center gap-2 rounded-xl border border-white/10 bg-white/5 px-4 py-2.5 text-xs font-bold text-gray-300 hover:bg-white/10 hover:text-white transition-colors">
                    <svg xmlns="http://www.w3.org/2000/svg" width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="4" y1="21" x2="4" y2="14"></line><line x1="4" y1="10" x2="4" y2="3"></line><line x1="12" y1="21" x2="12" y2="12"></line><line x1="12" y1="8" x2="12" y2="3"></line><line x1="20" y1="21" x2="20" y2="16"></line><line x1="20" y1="12" x2="20" y2="3"></line><line x1="1" y1="14" x2="7" y2="14"></line><line x1="9" y1="8" x2="15" y2="8"></line><line x1="17" y1="16" x2="23" y2="16"></line></svg>
                    Advanced
                </button>
                
                <!-- Create Button -->
                <button class="flex items-center gap-2 rounded-xl bg-gradient-to-r from-[#ff6b3d] to-[#ff3d71] px-6 py-3 text-sm font-bold text-white transition-all hover:opacity-90 hover:scale-[1.02] shadow-lg shadow-orange-500/20">
                    <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"><path d="m12 3-1.912 5.813a2 2 0 0 1-1.275 1.275L3 12l5.813 1.912a2 2 0 0 1 1.275 1.275L12 21l1.912-5.813a2 2 0 0 1 1.275-1.275L21 12l-5.813-1.912a2 2 0 0 1-1.275-1.275L12 3Z"/></svg>
                    Create
                </button>
            </div>
        </div>
    </div>

    <!-- Floating Cards -->
    <!-- Left Card -->
    <div class="absolute left-[-180px] top-[100px] hidden w-[280px] -rotate-6 transition-transform duration-500 hover:rotate-0 lg:block group cursor-pointer z-20">
        <div class="relative aspect-[3/4] w-full overflow-hidden rounded-2xl bg-gray-900 shadow-2xl border border-white/10">
            <img src="https://images.unsplash.com/photo-1534528741775-53994a69daeb?q=80&w=1000&auto=format&fit=crop" alt="Album Art" class="h-full w-full object-cover opacity-80 transition-transform duration-700 group-hover:scale-110" />
            <div class="absolute inset-0 bg-gradient-to-b from-transparent via-transparent to-black/90"></div>
            
            <!-- Play Button -->
            <div class="absolute bottom-24 left-5 h-12 w-12 rounded-full bg-white/10 backdrop-blur-md flex items-center justify-center hover:bg-white/20 transition-colors border border-white/10">
                <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="white" stroke="currentColor" stroke-width="0"><polygon points="5 3 19 12 5 21 5 3"></polygon></svg>
            </div>

            <div class="absolute bottom-0 left-0 w-full p-5 text-left">
                <h3 class="font-bold text-white text-xl leading-tight mb-2">goth girl knife fight.</h3>
                <div class="flex items-center gap-2">
                    <div class="h-5 w-5 rounded-full bg-gray-600 overflow-hidden ring-1 ring-white/20">
                        <img src="https://images.unsplash.com/photo-1534528741775-53994a69daeb?q=80&w=100&auto=format&fit=crop" class="w-full h-full object-cover" />
                    </div>
                    <p class="text-sm text-gray-300 font-medium">@astronaut</p>
                </div>
            </div>
        </div>
    </div>

    <!-- Right Card -->
    <div class="absolute right-[-180px] top-[180px] hidden w-[280px] rotate-6 transition-transform duration-500 hover:rotate-0 lg:block group cursor-pointer z-20">
        <div class="relative aspect-[3/4] w-full overflow-hidden rounded-2xl bg-gray-900 shadow-2xl border border-white/10">
            <img src="https://images.unsplash.com/photo-1470225620780-dba8ba36b745?q=80&w=1000&auto=format&fit=crop" alt="Album Art" class="h-full w-full object-cover opacity-80 transition-transform duration-700 group-hover:scale-110" />
            <div class="absolute inset-0 bg-gradient-to-b from-transparent via-transparent to-black/90"></div>
            
            <!-- Play Button -->
            <div class="absolute bottom-24 left-5 h-12 w-12 rounded-full bg-white/10 backdrop-blur-md flex items-center justify-center hover:bg-white/20 transition-colors border border-white/10">
                <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="white" stroke="currentColor" stroke-width="0"><polygon points="5 3 19 12 5 21 5 3"></polygon></svg>
            </div>

            <div class="absolute bottom-0 left-0 w-full p-5 text-left">
                <h3 class="font-bold text-white text-xl leading-tight mb-2">Lo-Fi Rocks</h3>
                <div class="flex items-center gap-2">
                    <div class="h-5 w-5 rounded-full bg-gray-600 overflow-hidden ring-1 ring-white/20">
                         <img src="https://images.unsplash.com/photo-1470225620780-dba8ba36b745?q=80&w=100&auto=format&fit=crop" class="w-full h-full object-cover" />
                    </div>
                    <p class="text-sm text-gray-300 font-medium">Stray Cat/Game Dev</p>
                </div>
            </div>
        </div>
    </div>

    <!-- Logos -->
    <div class="mt-12 flex flex-wrap items-center justify-center gap-10 md:gap-20 opacity-40 grayscale transition-opacity hover:opacity-60">
      <!-- Rolling Stone -->
      <svg class="h-5 md:h-7 w-auto" viewBox="0 0 130 24" fill="currentColor">
         <text x="0" y="20" font-family="serif" font-weight="bold" font-size="24">RollingStone</text>
      </svg>
      <!-- Variety -->
      <svg class="h-5 md:h-7 w-auto" viewBox="0 0 100 24" fill="currentColor">
         <text x="0" y="20" font-family="sans-serif" font-weight="bold" font-size="20" letter-spacing="2">VARIETY</text>
      </svg>
      <!-- Wired -->
      <svg class="h-5 md:h-7 w-auto" viewBox="0 0 80 24" fill="currentColor">
         <text x="0" y="20" font-family="monospace" font-weight="bold" font-size="22" letter-spacing="-1">WIRED</text>
      </svg>
      <!-- Billboard -->
      <svg class="h-5 md:h-7 w-auto" viewBox="0 0 120 24" fill="currentColor">
         <text x="0" y="20" font-family="sans-serif" font-weight="900" font-style="italic" font-size="24">billboard</text>
      </svg>
      <!-- Complex -->
      <svg class="h-5 md:h-7 w-auto" viewBox="0 0 110 24" fill="currentColor">
         <text x="0" y="20" font-family="sans-serif" font-weight="bold" font-size="20" letter-spacing="2">COMPLEX</text>
      </svg>
    </div>
  </div>
</section>
