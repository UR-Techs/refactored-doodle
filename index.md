---
layout: default
title: Refactored Doodle
---

<!-- Tailwind CDN -->
<link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">

<!-- Hero Section -->
<section class="bg-gradient-to-r from-indigo-500 via-purple-500 to-pink-500 text-white py-20 px-4 text-center">
  <h1 class="text-4xl md:text-6xl font-bold mb-4">Refactored Doodle</h1>
  <p class="text-xl md:text-2xl">A developer's sketchpad of learning, building, and sharing.</p>
</section>

<!-- About Section -->
<section class="max-w-4xl mx-auto py-12 px-4">
  <h2 class="text-3xl font-semibold mb-4">👋 About This Site</h2>
  <p class="text-lg text-gray-700">
    Refactored Doodle is a personal playground — part blog, part portfolio — where I share my coding journey,
    ideas, side-projects, and the occasional tech rant. Expect creative chaos and honest experiments.
  </p>
</section>

<!-- Blog Section -->
<section class="bg-gray-100 py-12 px-4">
  <div class="max-w-4xl mx-auto">
    <h2 class="text-3xl font-semibold mb-6">📝 Latest Blog Posts</h2>
    <ul class="space-y-4">
      {% for post in site.posts limit:3 %}
      <li class="bg-white shadow-md p-6 rounded-xl">
        <a href="{{ post.url }}" class="text-2xl font-semibold text-indigo-600 hover:underline">{{ post.title }}</a>
        <p class="text-gray-600 text-sm">{{ post.date | date: "%B %d, %Y" }}</p>
        <p class="mt-2 text-gray-800">{{ post.excerpt | strip_html | truncate: 160 }}</p>
      </li>
      {% endfor %}
    </ul>
    <div class="mt-6 text-right">
      <a href="/blog" class="text-indigo-600 font-semibold hover:underline">View All Posts →</a>
    </div>
  </div>
</section>

<!-- Projects Section -->
<section class="max-w-4xl mx-auto py-12 px-4">
  <h2 class="text-3xl font-semibold mb-6">💡 Featured Projects</h2>
  <div class="grid gap-6 md:grid-cols-2">
    <!-- Example Project Card -->
    <div class="bg-white p-6 rounded-xl shadow-md">
      <h3 class="text-2xl font-semibold mb-2">Project Name</h3>
      <p class="text-gray-700 mb-4">Short description of the project, what it does, and what you learned.</p>
      <a href="https://github.com/UR-Techs/project-repo" target="_blank" class="text-indigo-600 hover:underline">View on GitHub</a>
    </div>
    <!-- Add more project cards here -->
  </div>
</section>

<!-- Footer -->
<footer class="bg-gray-800 text-white text-center py-6">
  <p>© 2025 Refactored Doodle — Made with 💻 and ☕</p>
</footer>
