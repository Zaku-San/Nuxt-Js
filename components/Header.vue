<template>
  <header class="bg-slate-700 text-white py-6">
    <div class="container mx-auto flex justify-between items-center">
      <div>
        <NuxtLink to="/" class="text-2xl font-bold">My Website</NuxtLink>
      </div>
      <nav class="flex items-center gap-6">
        <NuxtLink to="/" class="text-lg hover:text-gray-300">Home</NuxtLink>
        <NuxtLink to="/about" class="text-lg hover:text-gray-300"
          >About</NuxtLink
        >
        <NuxtLink to="/contact" class="text-lg hover:text-gray-300"
          >Contact</NuxtLink
        >
      </nav>
    </div>
  </header>
</template>
