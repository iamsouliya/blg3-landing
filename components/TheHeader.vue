<script setup>
</script>

<template>
  <header class="bg-primary text-white py-4 shadow-lg">
    <div class="container mx-auto flex justify-between items-center">
      <h1 class="text-2xl font-bold">
        Blue Lagoon 3
      </h1>
      <nav class="flex space-x-4">
        <NuxtLink to="/" class="hover:text-turquoise-blue hover:underline">
          Home
        </NuxtLink>
        <NuxtLink to="/about" class="hover:text-turquoise-blue hover:underline">
          About
        </NuxtLink>
        <NuxtLink to="/gallery" class="hover:text-turquoise-blue hover:underline">
          Gallery
        </NuxtLink>
        <NuxtLink to="/contact" class="hover:text-turquoise-blue hover:underline">
          Contact
        </NuxtLink>
      </nav>
    </div>
  </header>
</template>

<style scoped>
.bg-forest-green {
  background-color: #228B22;
}
.hover\:text-turquoise-blue:hover {
  color: #40E0D0;
}
</style>
