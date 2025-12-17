<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Pixel Dojo – AI Creative Tools</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    body { background: radial-gradient(1200px 600px at 50% 0%, rgba(168,85,247,0.25), transparent 60%), #020617; }
  </style>
</head>
<body class="text-white">

<!-- NAVBAR -->
<nav class="fixed top-0 inset-x-0 z-50 bg-gradient-to-r from-purple-900/95 to-indigo-900/95 backdrop-blur border-b border-white/10">
  <div class="max-w-7xl mx-auto px-6 h-16 flex items-center justify-between">
    <div class="flex items-center gap-3">
      <div class="w-9 h-9 rounded-full bg-gradient-to-br from-purple-500 to-pink-500"></div>
      <span class="font-bold text-lg tracking-wide">PIXEL DOJO</span>
    </div>
    <div class="hidden md:flex items-center gap-6 text-sm">
      <a href="#" class="hover:text-purple-300">AI Images</a>
      <a href="#" class="hover:text-purple-300">AI Videos</a>
      <a href="#" class="hover:text-purple-300">Creator Studio</a>
      <a href="#" class="hover:text-purple-300">LoRAs</a>
      <a href="#" class="hover:text-purple-300">Prompts</a>
      <a href="#" class="hover:text-purple-300">News</a>
    </div>
    <div class="flex items-center gap-3">
      <button class="text-sm text-gray-300 hover:text-white">Sign In</button>
      <button class="px-4 py-1.5 rounded-lg bg-gradient-to-r from-pink-500 to-purple-500 text-sm font-semibold">Subscribe</button>
    </div>
  </div>
</nav>

<!-- HERO -->
<section class="pt-32 pb-20 relative overflow-hidden">
  <div class="absolute inset-0 bg-[linear-gradient(rgba(255,255,255,0.03)_1px,transparent_1px),linear-gradient(90deg,rgba(255,255,255,0.03)_1px,transparent_1px)] bg-[size:64px_64px]"></div>
  <div class="absolute top-0 left-1/2 -translate-x-1/2 w-[900px] h-[400px] bg-purple-600/20 blur-[120px]"></div>

  <div class="relative max-w-4xl mx-auto text-center px-6">
    <div class="inline-flex items-center gap-2 px-4 py-2 rounded-full bg-purple-500/10 border border-purple-500/20 text-sm mb-6">
      <span class="w-2 h-2 bg-green-400 rounded-full"></span>
      NEW MODELS WEEKLY · 60+ Models · $25/mo
    </div>

    <h1 class="text-4xl sm:text-6xl lg:text-7xl font-extrabold tracking-tight mb-6">
      Every <span class="bg-clip-text text-transparent bg-gradient-to-r from-purple-400 to-pink-400 underline decoration-purple-400/50">AI Creative Tool</span><br />
      in One Place
    </h1>

    <p class="text-lg text-gray-400 max-w-2xl mx-auto mb-10">
      Access Flux 2, WAN, Veo 3.1, Imagen 4, and 60+ cutting-edge models.<br />
      Save hundreds vs. separate subscriptions.
    </p>

    <div class="flex justify-center gap-4">
      <button class="px-8 py-3 rounded-xl bg-gradient-to-r from-purple-500 to-pink-500 font-semibold text-lg shadow-lg">Start Creating</button>
      <button class="px-8 py-3 rounded-xl border border-white/20 text-lg hover:bg-white/5">View Pricing</button>
    </div>
  </div>
</section>

<!-- VIDEO / IMAGE PREVIEW -->
<section class="max-w-6xl mx-auto px-6 pb-24">
  <div class="relative rounded-2xl overflow-hidden border border-purple-500/30 bg-black shadow-2xl">
    <div class="aspect-video flex items-center justify-center bg-gray-900">
      <div class="text-gray-400">AI Generated Showcase</div>
    </div>
    <div class="absolute top-4 left-4 px-3 py-1 rounded-full bg-black/60 border border-white/10 text-xs">🔴 AI Generated</div>
  </div>
</section>

<!-- FEATURES -->
<section class="max-w-7xl mx-auto px-6 pb-24">
  <div class="grid grid-cols-2 lg:grid-cols-4 gap-6">
    <div class="rounded-2xl p-6 bg-white/5 border border-white/10">
      <h3 class="font-bold mb-2">60+ AI Models</h3>
      <p class="text-sm text-gray-400">Flux, WAN, Veo, Imagen & more</p>
    </div>
    <div class="rounded-2xl p-6 bg-white/5 border border-white/10">
      <h3 class="font-bold mb-2">One Subscription</h3>
      <p class="text-sm text-gray-400">Replace 10+ platforms</p>
    </div>
    <div class="rounded-2xl p-6 bg-white/5 border border-white/10">
      <h3 class="font-bold mb-2">Instant Results</h3>
      <p class="text-sm text-gray-400">Generate in seconds</p>
    </div>
    <div class="rounded-2xl p-6 bg-white/5 border border-white/10">
      <h3 class="font-bold mb-2">Commercial Rights</h3>
      <p class="text-sm text-gray-400">You own what you create</p>
    </div>
  </div>
</section>

<!-- FOOTER -->
<footer class="border-t border-white/10 py-10 text-center text-sm text-gray-500">
  © 2025 Pixel Dojo · Demo clone for learning
</footer>

</body>
</html>
