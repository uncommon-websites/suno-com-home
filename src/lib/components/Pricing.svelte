<script>
  // Pricing Section
  let isYearly = true;
</script>

<section class="bg-[#0a0a0a] py-24 text-white">
  <div class="container mx-auto px-6 max-w-7xl">
    <div class="mb-16 text-center">
      <h2 class="mb-4 text-4xl font-bold md:text-6xl tracking-tight leading-[1.1]">Start making music<br />for free</h2>
      <p class="mb-8 text-gray-400 text-lg">Select the plan that best fits your needs</p>
      
      <div class="flex items-center justify-center gap-4 text-sm">
        <span class={!isYearly ? "text-white font-medium" : "text-gray-500"}>Monthly</span>
        <button 
          class="relative h-7 w-12 rounded-full bg-gray-800 transition-colors focus:outline-none"
          on:click={() => isYearly = !isYearly}
        >
          <span class={`absolute top-1 h-5 w-5 rounded-full bg-white transition-all duration-300 shadow-sm ${isYearly ? "left-6" : "left-1"}`}></span>
        </button>
        <span class={isYearly ? "text-white font-medium" : "text-gray-500"}>Yearly <span class="ml-1 rounded bg-white/10 px-1.5 py-0.5 text-[10px] font-bold text-white uppercase tracking-wide">SAVE 20%</span></span>
      </div>
    </div>

    <div class="grid grid-cols-1 gap-6 md:grid-cols-3">
      <!-- Free Plan -->
      <div class="flex flex-col rounded-3xl bg-[#121212] p-8 border border-white/5 hover:border-white/10 transition-colors">
        <h3 class="mb-2 text-2xl font-bold">Free Plan</h3>
        <p class="mb-6 text-sm text-gray-400">Our starter plan.</p>
        <div class="mb-8 flex items-baseline gap-1">
          <span class="text-4xl font-bold tracking-tight">$0</span>
          <span class="text-sm text-gray-500">/month</span>
        </div>
        
        <button class="mb-8 w-full rounded-full bg-white/10 py-3 text-sm font-bold text-white transition-colors hover:bg-white/20">Sign Up</button>
        
        <ul class="space-y-4 text-sm text-gray-400">
          <li class="flex items-start gap-3">
            <svg class="mt-0.5 h-4 w-4 flex-shrink-0 text-white" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="3"><path stroke-linecap="round" stroke-linejoin="round" d="M5 13l4 4L19 7" /></svg>
            Access to v4.5-all
          </li>
          <li class="flex items-start gap-3">
            <svg class="mt-0.5 h-4 w-4 flex-shrink-0 text-white" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="3"><path stroke-linecap="round" stroke-linejoin="round" d="M5 13l4 4L19 7" /></svg>
            50 credits renew daily (10 songs)
          </li>
          <li class="flex items-start gap-3 text-gray-500">
            <svg class="mt-0.5 h-4 w-4 flex-shrink-0 text-gray-600" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="3"><path stroke-linecap="round" stroke-linejoin="round" d="M6 18L18 6M6 6l12 12" /></svg>
            No commercial use
          </li>
          <li class="flex items-start gap-3">
            <svg class="mt-0.5 h-4 w-4 flex-shrink-0 text-white" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="3"><path stroke-linecap="round" stroke-linejoin="round" d="M5 13l4 4L19 7" /></svg>
            Standard features only
          </li>
          <li class="flex items-start gap-3">
            <svg class="mt-0.5 h-4 w-4 flex-shrink-0 text-white" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="3"><path stroke-linecap="round" stroke-linejoin="round" d="M5 13l4 4L19 7" /></svg>
            Upload up to 1 min of audio
          </li>
          <li class="flex items-start gap-3">
            <svg class="mt-0.5 h-4 w-4 flex-shrink-0 text-white" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="3"><path stroke-linecap="round" stroke-linejoin="round" d="M5 13l4 4L19 7" /></svg>
            Shared creation queue
          </li>
          <li class="flex items-start gap-3 text-gray-500">
            <svg class="mt-0.5 h-4 w-4 flex-shrink-0 text-gray-600" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="3"><path stroke-linecap="round" stroke-linejoin="round" d="M6 18L18 6M6 6l12 12" /></svg>
            No add-on credit purchases
          </li>
        </ul>
      </div>

      <!-- Pro Plan -->
      <div class="relative flex flex-col rounded-3xl bg-[#121212] p-8 ring-1 ring-white/20 shadow-2xl shadow-purple-900/10">
        <div class="absolute right-6 top-6 rounded-full bg-gradient-to-r from-pink-500 to-purple-600 px-3 py-1 text-[10px] font-bold uppercase text-white tracking-wider flex items-center gap-1">
            <svg xmlns="http://www.w3.org/2000/svg" width="10" height="10" viewBox="0 0 24 24" fill="currentColor" stroke="none"><path d="M12 2l3.09 6.26L22 9.27l-5 4.87 1.18 6.88L12 17.77l-6.18 3.25L7 14.14 2 9.27l6.91-1.01L12 2z"></path></svg>
            Most Popular
        </div>
        <h3 class="mb-2 text-2xl font-bold">Pro Plan</h3>
        <p class="mb-6 text-sm text-gray-400">Access to our best models and editing tools.</p>
        <div class="mb-2 flex items-baseline gap-1">
          <span class="text-4xl font-bold tracking-tight">$8</span>
          <span class="text-sm text-gray-500">/month</span>
        </div>
        <p class="mb-6 text-xs text-gray-500">Saves $24 by billing yearly!<br>Taxes calculated at checkout</p>
        
        <button class="mb-8 w-full rounded-full bg-white py-3 text-sm font-bold text-black transition-transform hover:scale-105 hover:bg-gray-100">Subscribe</button>
        
        <ul class="space-y-4 text-sm text-gray-400">
          <li class="flex items-start gap-3">
            <svg class="mt-0.5 h-4 w-4 flex-shrink-0 text-white" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="3"><path stroke-linecap="round" stroke-linejoin="round" d="M5 13l4 4L19 7" /></svg>
            Access to latest and most advanced v5 model
          </li>
          <li class="flex items-start gap-3">
            <svg class="mt-0.5 h-4 w-4 flex-shrink-0 text-white" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="3"><path stroke-linecap="round" stroke-linejoin="round" d="M5 13l4 4L19 7" /></svg>
            2,500 credits (up to 500 songs), refreshes monthly
          </li>
          <li class="flex items-start gap-3">
            <svg class="mt-0.5 h-4 w-4 flex-shrink-0 text-white" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="3"><path stroke-linecap="round" stroke-linejoin="round" d="M5 13l4 4L19 7" /></svg>
            Commercial use rights for new songs made
          </li>
          <li class="flex items-start gap-3">
            <svg class="mt-0.5 h-4 w-4 flex-shrink-0 text-white" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="3"><path stroke-linecap="round" stroke-linejoin="round" d="M5 13l4 4L19 7" /></svg>
            Standard + Pro features (personas and advanced editing)
          </li>
          <li class="flex items-start gap-3">
            <svg class="mt-0.5 h-4 w-4 flex-shrink-0 text-white" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="3"><path stroke-linecap="round" stroke-linejoin="round" d="M5 13l4 4L19 7" /></svg>
            Split songs into up to 12 vocal and instrument stems
          </li>
          <li class="flex items-start gap-3">
            <svg class="mt-0.5 h-4 w-4 flex-shrink-0 text-white" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="3"><path stroke-linecap="round" stroke-linejoin="round" d="M5 13l4 4L19 7" /></svg>
            Upload up to 8 min of audio
          </li>
          <li class="flex items-start gap-3">
            <svg class="mt-0.5 h-4 w-4 flex-shrink-0 text-white" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="3"><path stroke-linecap="round" stroke-linejoin="round" d="M5 13l4 4L19 7" /></svg>
            Add new vocals or instrumentals to existing songs
          </li>
          <li class="flex items-start gap-3">
            <svg class="mt-0.5 h-4 w-4 flex-shrink-0 text-white" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="3"><path stroke-linecap="round" stroke-linejoin="round" d="M5 13l4 4L19 7" /></svg>
            Early access to new features
          </li>
          <li class="flex items-start gap-3">
            <svg class="mt-0.5 h-4 w-4 flex-shrink-0 text-white" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="3"><path stroke-linecap="round" stroke-linejoin="round" d="M5 13l4 4L19 7" /></svg>
            Ability to purchase add-on credits
          </li>
          <li class="flex items-start gap-3">
            <svg class="mt-0.5 h-4 w-4 flex-shrink-0 text-white" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="3"><path stroke-linecap="round" stroke-linejoin="round" d="M5 13l4 4L19 7" /></svg>
            Priority queue, up to 10 songs at once
          </li>
        </ul>
      </div>

      <!-- Premier Plan -->
      <div class="relative flex flex-col rounded-3xl bg-[#121212] p-8 border border-white/5 hover:border-white/10 transition-colors">
        <div class="absolute right-6 top-6 rounded bg-white/10 px-2 py-1 text-[10px] font-bold uppercase text-white tracking-wider">Best Value</div>
        <h3 class="mb-2 text-2xl font-bold">Premier Plan</h3>
        <p class="mb-6 text-sm text-gray-400">Maximum credits and every feature unlocked.</p>
        <div class="mb-2 flex items-baseline gap-1">
          <span class="text-4xl font-bold tracking-tight">$24</span>
          <span class="text-sm text-gray-500">/month</span>
        </div>
        <p class="mb-6 text-xs text-gray-500">Saves $72 by billing yearly!<br>Taxes calculated at checkout</p>
        
        <button class="mb-8 w-full rounded-full bg-white/10 py-3 text-sm font-bold text-white transition-colors hover:bg-white/20">Subscribe</button>
        
        <ul class="space-y-4 text-sm text-gray-400">
          <li class="flex items-start gap-3">
            <svg class="mt-0.5 h-4 w-4 flex-shrink-0 text-white" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="3"><path stroke-linecap="round" stroke-linejoin="round" d="M5 13l4 4L19 7" /></svg>
            Access to Suno Studio
          </li>
          <li class="flex items-start gap-3">
            <svg class="mt-0.5 h-4 w-4 flex-shrink-0 text-white" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="3"><path stroke-linecap="round" stroke-linejoin="round" d="M5 13l4 4L19 7" /></svg>
            Access to latest and most advanced v5 model
          </li>
          <li class="flex items-start gap-3">
            <svg class="mt-0.5 h-4 w-4 flex-shrink-0 text-white" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="3"><path stroke-linecap="round" stroke-linejoin="round" d="M5 13l4 4L19 7" /></svg>
            10,000 credits (up to 2,000 songs), refreshes monthly
          </li>
          <li class="flex items-start gap-3">
            <svg class="mt-0.5 h-4 w-4 flex-shrink-0 text-white" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="3"><path stroke-linecap="round" stroke-linejoin="round" d="M5 13l4 4L19 7" /></svg>
            Commercial use rights for new songs made
          </li>
          <li class="flex items-start gap-3">
            <svg class="mt-0.5 h-4 w-4 flex-shrink-0 text-white" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="3"><path stroke-linecap="round" stroke-linejoin="round" d="M5 13l4 4L19 7" /></svg>
            Standard + Pro features (personas and advanced editing)
          </li>
          <li class="flex items-start gap-3">
            <svg class="mt-0.5 h-4 w-4 flex-shrink-0 text-white" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="3"><path stroke-linecap="round" stroke-linejoin="round" d="M5 13l4 4L19 7" /></svg>
            Split songs into up to 12 vocal and instrument stems
          </li>
          <li class="flex items-start gap-3">
            <svg class="mt-0.5 h-4 w-4 flex-shrink-0 text-white" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="3"><path stroke-linecap="round" stroke-linejoin="round" d="M5 13l4 4L19 7" /></svg>
            Upload up to 8 min of audio
          </li>
          <li class="flex items-start gap-3">
            <svg class="mt-0.5 h-4 w-4 flex-shrink-0 text-white" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="3"><path stroke-linecap="round" stroke-linejoin="round" d="M5 13l4 4L19 7" /></svg>
            Add new vocals or instrumentals to existing songs
          </li>
          <li class="flex items-start gap-3">
            <svg class="mt-0.5 h-4 w-4 flex-shrink-0 text-white" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="3"><path stroke-linecap="round" stroke-linejoin="round" d="M5 13l4 4L19 7" /></svg>
            Early access to new features
          </li>
          <li class="flex items-start gap-3">
            <svg class="mt-0.5 h-4 w-4 flex-shrink-0 text-white" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="3"><path stroke-linecap="round" stroke-linejoin="round" d="M5 13l4 4L19 7" /></svg>
            Ability to purchase add-on credits
          </li>
          <li class="flex items-start gap-3">
            <svg class="mt-0.5 h-4 w-4 flex-shrink-0 text-white" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="3"><path stroke-linecap="round" stroke-linejoin="round" d="M5 13l4 4L19 7" /></svg>
            Priority queue, up to 10 songs at once
          </li>
        </ul>
      </div>
    </div>
  </div>
</section>
