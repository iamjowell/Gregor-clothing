# Gregor-clothing
<!DOCTYPE html>
<html lang="en" class="bg-white text-black dark:bg-gray-900 dark:text-white">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Gregor Clothing</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    tailwind.config = {
      darkMode: 'class',
    }
  </script>
</head>
<body class="min-h-screen font-sans transition-all duration-300">

  <!-- Navbar -->
  <header class="flex justify-between items-center p-4 shadow-md">
    <h1 class="text-2xl font-bold">Gregor</h1>
    <div class="flex items-center gap-4">
      <a href="#login" class="text-sm font-medium hover:underline">Login</a>
      <button onclick="toggleTheme()" class="bg-gray-200 dark:bg-gray-800 p-2 rounded">
        🌓
      </button>
    </div>
  </header>

  <!-- Hero Section -->
  <section class="text-center py-12 px-4">
    <h2 class="text-3xl font-bold mb-4">Welcome to Gregor Clothing</h2>
    <p class="max-w-xl mx-auto text-lg text-gray-600 dark:text-gray-300">
      Discover top-quality fashion with Gregor. From jeans and joggers to shirts and hoodies,
      we blend comfort and style for your everyday wear.
    </p>
  </section>

  <!-- Clothing Sections -->
  <section class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-4 gap-6 p-6">
    <div class="p-4 rounded-xl shadow-md bg-white dark:bg-gray-800">
      <h3 class="text-xl font-semibold mb-2">Jeans Wear</h3>
      <p>Durable and stylish denim for all-day comfort.</p>
    </div>
    <div class="p-4 rounded-xl shadow-md bg-white dark:bg-gray-800">
      <h3 class="text-xl font-semibold mb-2">Joggers</h3>
      <p>Relaxed fits and athletic styles for modern motion.</p>
    </div>
    <div class="p-4 rounded-xl shadow-md bg-white dark:bg-gray-800">
      <h3 class="text-xl font-semibold mb-2">Shirts</h3>
      <p>Casual to formal, we've got your top half covered.</p>
    </div>
    <div class="p-4 rounded-xl shadow-md bg-white dark:bg-gray-800">
      <h3 class="text-xl font-semibold mb-2">Hoodies</h3>
      <p>Cozy layers with clean designs and bold colors.</p>
    </div>
  </section>

  <!-- Login Section -->
  <section id="login" class="max-w-md mx-auto my-12 p-6 bg-white dark:bg-gray-800 rounded-xl shadow-lg">
    <h2 class="text-2xl font-bold mb-4 text-center">Login</h2>
    <form class="space-y-4">
      <input type="email" placeholder="Email" class="w-full p-3 border rounded dark:bg-gray-700 dark:border-gray-600">
      <input type="password" placeholder="Password" class="w-full p-3 border rounded dark:bg-gray-700 dark:border-gray-600">
      <button type="submit" class="w-full bg-black text-white p-3 rounded hover:bg-gray-800">Sign In</button>
    </form>
  </section>

  <!-- Footer -->
  <footer class="text-center text-sm p-4 bg-gray-100 dark:bg-gray-800 dark:text-gray-400">
    &copy; 2025 Gregor Clothing. All rights reserved.
  </footer>

  <!-- Dark Mode Toggle Script -->
  <script>
    function toggleTheme() {
      document.documentElement.classList.toggle('dark');
    }
  </script>

</body>
</html>
