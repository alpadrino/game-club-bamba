<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Game Club Bamba</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    function bookWhatsApp() {
      const name = document.getElementById('name').value;
      const time = document.getElementById('time').value;
      const duration = document.getElementById('duration').value;
      const game = document.getElementById('game').value;
      const message = `🎮 Game Club Bamba Booking\nName: ${name}\nTime: ${time}\nDuration: ${duration}\nGame: ${game}`;
      window.open(`https://wa.me/21628765163?text=${encodeURIComponent(message)}`, '_blank');
    }
  </script>
</head>
<body class="bg-black text-white font-sans scroll-smooth">

<!-- Navbar -->
<nav class="flex justify-between items-center p-5 bg-gray-900 sticky top-0 z-50 shadow-lg">
  <h1 class="text-2xl font-bold text-purple-500">🎮 Game Club Bamba</h1>
  <div class="space-x-4 hidden md:block">
    <a href="#home">Home</a>
    <a href="#games">Games</a>
    <a href="#pricing">Pricing</a>
    <a href="#gallery">Gallery</a>
    <a href="#booking">Booking</a>
    <a href="#contact">Contact</a>
  </div>
</nav>

<!-- Hero -->
<section id="home" class="text-center py-24 bg-gradient-to-r from-black via-purple-900 to-black">
  <h2 class="text-5xl font-bold mb-4">Ultimate Gaming Experience</h2>
  <p class="mb-6 text-gray-300">Mourouj 6 - Premium PS5 Gaming Lounge</p>
  <p class="text-green-400 mb-4">🌙 Ramadan Kareem - Night Gaming Available</p>
  <a href="#booking" class="bg-purple-600 px-8 py-3 rounded-xl">Book Now</a>
</section>

<!-- Games -->
<section id="games" class="p-10">
  <h2 class="text-3xl mb-6">Top Games</h2>
  <div class="grid grid-cols-2 md:grid-cols-3 gap-6">
    <div class="bg-gray-800 p-6 rounded-xl">FC 26</div>
    <div class="bg-gray-800 p-6 rounded-xl">GTA V</div>
    <div class="bg-gray-800 p-6 rounded-xl">Call of Duty</div>
    <div class="bg-gray-800 p-6 rounded-xl">Red Dead Redemption</div>
    <div class="bg-gray-800 p-6 rounded-xl">Valorant</div>
    <div class="bg-gray-800 p-6 rounded-xl">More...</div>
  </div>
</section>

<!-- Pricing -->
<section id="pricing" class="p-10 bg-gray-900 text-center">
  <h2 class="text-3xl mb-6">Pricing</h2>
  <p>10 min - 1 DT | 20 min - 2 DT | 30 min - 3 DT | 60 min - 6 DT</p>
</section>

<!-- Gallery -->
