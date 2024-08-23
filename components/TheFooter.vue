<script setup>
</script>

<template>
  <footer class="bg-dark-slate-gray text-white p-6 mt-10">
    <div class="container mx-auto text-center">
      <p>&copy; 2024 Blue Lagoon 3. All Rights Reserved.</p>
      <div class="mt-4 space-x-4">
        <NuxtLink to="/" class="hover:text-turquoise-blue">
          Home
        </NuxtLink>
        <NuxtLink to="/about" class="hover:text-turquoise-blue">
          About
        </NuxtLink>
        <NuxtLink to="/contact" class="hover:text-turquoise-blue">
          Contact
        </NuxtLink>
      </div>
      <div class="mt-4">
        <NuxtLink href="https://facebook.com" target="_blank" class="hover:text-turquoise-blue">
          Facebook
        </NuxtLink>
        <NuxtLink href="https://instagram.com" target="_blank" class="ml-4 hover:text-turquoise-blue">
          Instagram
        </NuxtLink>
      </div>
    </div>
  </footer>
</template>

<style scoped>
.bg-dark-slate-gray {
  background-color: #2F4F4F;
}
.hover\:text-turquoise-blue:hover {
  color: #40E0D0;
}
</style>
