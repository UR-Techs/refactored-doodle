<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Refactored Doodle</title>
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@3.3.2/dist/tailwind.min.css" rel="stylesheet">
</head>
<body class="bg-gradient-to-br from-slate-900 to-indigo-900 text-white min-h-screen font-sans">

  <!-- NAVIGATION -->
  <header class="bg-slate-950/50 backdrop-blur-md py-4 shadow-md sticky top-0 z-50">
    <div class="container mx-auto px-6 flex justify-between items-center">
      <h1 class="text-2xl font-bold tracking-wide">Refactored Doodle</h1>
      <nav>
        <ul class="flex space-x-6 text-sm">
          <li><a href="#about" class="hover:text-indigo-300 transition">About</a></li>
          <li><a href="#features" class="hover:text-indigo-300 transition">Features</a></li>
          <li><a href="#contact" class="hover:text-indigo-300 transition">Contact</a></li>
          <li><a href="https://github.com/YOUR_USERNAME/refactored-doodle" target="_blank" class="text-indigo-400 hover:underline">GitHub</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <!-- HERO -->
  <section class="text-center py-24 px-6">
    <h2 class="text-4xl md:text-6xl font-bold mb-4">Welcome to Refactored Doodle 🎨</h2>
    <p class="text-lg md:text-xl max-w-2xl mx-auto text-slate-300 mb-8">
      A creative blend of code and concept, crafted to showcase clean design, elegant logic, and fun experimentation.
    </p>
    <a href="#about" class="bg-indigo-500 hover:bg-indigo-600 text-white px-6 py-3 rounded-full shadow-md transition">Explore More</a>
  </section>

  <!-- ABOUT -->
  <section id="about" class="py-20 px-6 bg-slate-800">
    <div class="max-w-4xl mx-auto text-center">
      <h3 class="text-3xl font-semibold mb-4">About the Project</h3>
      <p class="text-slate-300 text-lg">
        Refactored Doodle is a portfolio project focused on <strong>modern UI/UX</strong>, reusable components, and responsive design. Built with love, logic, and lots of caffeine ☕.
      </p>
    </div>
  </section>

  <!-- FEATURES -->
  <section id="features" class="py-20 px-6">
    <div class="max-w-5xl mx-auto text-center">
      <h3 class="text-3xl font-semibold mb-12">Features</h3>
      <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
        <div class="bg-slate-800 p-6 rounded-xl shadow-md hover:scale-105 transition">
          <h4 class="text-xl font-semibold mb-2">Clean UI</h4>
          <p class="text-slate-300">Tailwind-powered minimalist design for readability and elegance.</p>
        </div>
        <div class="bg-slate-800 p-6 rounded-xl shadow-md hover:scale-105 transition">
          <h4 class="text-xl font-semibold mb-2">Modular Code</h4>
          <p class="text-slate-300">Built to be refactored, extended, and understood easily.</p>
        </div>
        <div class="bg-slate-800 p-6 rounded-xl shadow-md hover:scale-105 transition">
          <h4 class="text-xl font-semibold mb-2">Fully Responsive</h4>
          <p class="text-slate-300">Looks great on desktop, tablet, and mobile screens.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- CONTACT -->
  <section id="contact" class="py-20 px-6 bg-slate-800">
    <div class="max-w-4xl mx-auto text-center">
      <h3 class="text-3xl font-semibold mb-6">Let’s Connect</h3>
      <p class="text-slate-300 mb-6">Want to collaborate or give feedback? Reach out!</p>
      <a href="mailto:your-email@example.com" class="inline-block bg-indigo-500 hover:bg-indigo-600 text-white px-6 py-3 rounded-full transition">
        Email Me
      </a>
    </div>
  </section>

  <!-- FOOTER -->
  <footer class="text-center py-6 text-slate-500 text-sm border-t border-slate-700">
    © 2025 Refactored Doodle. Built with ♥ by Urooj Rafiq.
  </footer>

</body>
</html>
```



