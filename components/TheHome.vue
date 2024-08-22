<!-- components/HomePage.vue -->
<script setup>
</script>

<template>
  <div class="space-y-16">
    <!-- Hero Section -->
    <section class="relative h-screen flex items-center justify-center bg-cover bg-center text-white" style="background-image: url('/images/blue-lagoon-3-hero.jpg');">
      <div class="absolute inset-0 bg-black opacity-50" />
      <div class="relative z-10 text-center max-w-lg">
        <h1 class="text-4xl font-bold">
          Welcome to Blue Lagoon 3
        </h1>
        <p class="mt-4 text-lg">
          Discover the serene beauty of Vang Vieng’s hidden gem.
        </p>
        <Button variant="primary" class="mt-8">
          Plan Your Visit
        </Button>
      </div>
    </section>

    <!-- About Section -->
    <section class="container mx-auto p-8 text-center">
      <h2 class="text-3xl font-semibold text-primary">
        About Blue Lagoon 3
      </h2>
      <p class="mt-4 text-muted-foreground">
        Blue Lagoon 3 is a tranquil oasis nestled in the lush greenery of Vang Vieng. Perfect for swimming, relaxing, and enjoying nature, this hidden gem offers an escape from the hustle and bustle.
      </p>
    </section>

    <!-- Gallery Section -->
    <section class="container mx-auto p-8">
      <h2 class="text-3xl font-semibold text-center text-primary">
        Gallery
      </h2>
      <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 gap-4 mt-8">
        <img src="" alt="Blue Lagoon 3" class="rounded-lg shadow-md">
        <img src="" alt="Blue Lagoon 3" class="rounded-lg shadow-md">
        <img src="" alt="Blue Lagoon 3" class="rounded-lg shadow-md">
      </div>
    </section>

    <!-- Activities Section -->
    <section class="container mx-auto p-8 text-center bg-secondary text-secondary-foreground rounded-lg shadow-lg">
      <h2 class="text-3xl font-semibold text-primary">
        Activities
      </h2>
      <p class="mt-4">
        Explore a range of activities at Blue Lagoon 3 including:
      </p>
      <ul class="mt-4 space-y-2 text-muted-foreground">
        <li>Swimming in crystal clear waters</li>
        <li>Hiking trails through the lush forest</li>
        <li>Relaxing on the natural stone benches</li>
        <li>Enjoying local Laotian food at the nearby restaurants</li>
      </ul>
    </section>

    <!-- Contact Section -->
    <section class="container mx-auto p-8 text-center">
      <h2 class="text-3xl font-semibold text-primary">
        Contact Us
      </h2>
      <p class="mt-4 text-muted-foreground">
        Want to know more? Reach out to us!
      </p>
      <div class="mt-8 space-y-4">
        <div>Email: <a href="mailto:info@bluelagoon3.com" class="text-primary hover:underline">info@bluelagoon3.com</a></div>
        <div>Phone: <a href="tel:+8562021234567" class="text-primary hover:underline">+856 20 2123 4567</a></div>
      </div>
    </section>
  </div>
</template>

<style scoped>
/* Add additional styling here if needed */
</style>
