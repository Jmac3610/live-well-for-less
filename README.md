# live-well-for-less
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Live Well for Less</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-100 text-gray-800">
  <!-- Hero Section -->
  <section class="relative bg-blue-600 text-white py-20 text-center">
    <img src="https://images.unsplash.com/photo-1507525428034-b723cf961d3e?auto=format&fit=crop&w=1500&q=80" alt="Beach" class="absolute inset-0 w-full h-full object-cover opacity-30" />
    <div class="relative z-10">
      <h1 class="text-4xl font-bold mb-4">Live Well for Less</h1>
      <p class="text-xl mb-6">Discover how cheaply (but comfortably) you can live around the world.</p>
      <input type="text" placeholder="Search a country..." class="px-4 py-2 rounded text-black" />
    </div>
  </section>

  <!-- Featured Countries -->
  <section class="py-10 px-6 max-w-6xl mx-auto">
    <h2 class="text-2xl font-bold mb-6">Featured Affordable Countries</h2>
    <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
      <!-- Thailand -->
      <div class="bg-white rounded-lg shadow p-6">
        <img src="https://images.unsplash.com/photo-1581847802297-9b4c3c9aa729?auto=format&fit=crop&w=600&q=60" alt="Thailand" class="w-full h-40 object-cover rounded mb-4">
        <h3 class="text-xl font-semibold mb-2">Thailand</h3>
        <p>Average cost: $900/month</p>
        <p>Great food, beaches, and digital nomad scene.</p>
        <p class="mt-2 text-sm text-gray-600">🧳 2-week experience: Enjoy Bangkok's street food, day trips to ancient temples, and a relaxing beach stay in Krabi — all under $450 for food, transport, and lodging.</p>
      </div>

      <!-- Portugal -->
      <div class="bg-white rounded-lg shadow p-6">
        <img src="https://images.unsplash.com/photo-1561043433-aaf687c4cf4e?auto=format&fit=crop&w=600&q=60" alt="Portugal" class="w-full h-40 object-cover rounded mb-4">
        <h3 class="text-xl font-semibold mb-2">Portugal</h3>
        <p>Average cost: $1,200/month</p>
        <p>Warm culture, excellent healthcare, and safety.</p>
        <p class="mt-2 text-sm text-gray-600">🧳 2-week experience: Stay in Lisbon or Porto, visit coastal villages, enjoy seafood and local wine. Total cost can be kept around $650–$800 with a cozy Airbnb and local transit.</p>
      </div>

      <!-- Mexico -->
      <div class="bg-white rounded-lg shadow p-6">
        <img src="https://images.unsplash.com/photo-1587840171670-8b850147754e?auto=format&fit=crop&w=600&q=60" alt="Mexico" class="w-full h-40 object-cover rounded mb-4">
        <h3 class="text-xl font-semibold mb-2">Mexico</h3>
        <p>Average cost: $850/month</p>
        <p>Affordable housing and rich culture.</p>
        <p class="mt-2 text-sm text-gray-600">🧳 2-week experience: Explore Mexico City or Oaxaca for amazing cuisine, art, and heritage. Expect to spend $400–$600 including food, local buses, and museums.</p>
      </div>
    </div>
  </section>

  <!-- Comparison Tool Preview -->
  <section class="bg-white py-12 px-6 mt-10">
    <h2 class="text-2xl font-bold mb-4 text-center">Compare to Your Country</h2>
    <p class="text-center mb-6">See how much further your money goes elsewhere.</p>
    <div class="max-w-xl mx-auto text-center">
      <input type="text" placeholder="Enter your city/country" class="px-4 py-2 rounded mb-4 w-full border" />
      <button class="bg-blue-600 text-white px-4 py-2 rounded">Compare</button>
    </div>
  </section>

  <!-- MegaAmerican Video Section -->
  <section class="bg-gray-200 py-12 px-6 mt-10">
    <h2 class="text-2xl font-bold mb-6 text-center">🌍 MegaAmerican Moments</h2>
    <p class="text-center mb-4">Featured nature & travel reel from MegaAmerican</p>
    <div class="flex justify-center">
      <blockquote class="instagram-media" data-instgrm-permalink="https://www.instagram.com/megaamerican/reel/DLYfRo_N6SI/?hl=en" data-instgrm-version="14" style="width:100%; max-width:540px"></blockquote>
    </div>
    <script async src="https://www.instagram.com/embed.js"></script>
  </section>

  <!-- Footer -->
  <footer class="bg-gray-800 text-white text-center py-6 mt-10">
    <p>&copy; 2025 Live Well for Less. All rights reserved.</p>
  </footer>
</body>
</html>
