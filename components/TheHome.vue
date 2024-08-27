<!-- components/HomePage.vue -->
<script setup>
import { Button } from '@/components/ui/button/'
import { Card } from '@/components/ui/card/'
</script>

<template>
  <div class="space-y-16">
    <!-- Hero Section -->
    <section class="relative h-screen flex items-center justify-center bg-cover bg-center text-white rounded-lg overflow-auto shadow-md" style="background-image: url('hero.jpg');">
      <div class="absolute inset-0 bg-black opacity-50" />
      <div class="relative z-10 text-center max-w-lg">
        <h1 class="text-4xl font-bold">
          Welcome to Blue Lagoon 3
        </h1>
        <p class="mt-4 text-lg">
          Discover the serene beauty of Vang Vieng’s hidden gem.
        </p>
        <Button class="mt-8">
          Plan Your Visit
        </Button>
      </div>
    </section>

    <!-- About Section -->
    <Card class="container mx-auto p-8 text-center shadow-md">
      <h2 class="text-3xl font-semibold text-primary">
        About Blue Lagoon 3
      </h2>
      <p class="mt-4 text-muted-foreground">
        Blue Lagoon 3 is a tranquil oasis nestled in the lush greenery of Vang Vieng. Perfect for swimming, relaxing, and enjoying nature, this hidden gem offers an escape from the hustle and bustle.
      </p>
    </Card>

    <!-- Gallery Section -->
    <section class="container mx-auto p-8">
      <h2 class="text-3xl font-semibold text-center text-primary">
        Gallery
      </h2>
      <ul class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 gap-4 mt-8">
        <li>
          <NuxtImg src="https://res.cloudinary.com/db2cje7en/image/upload/v1724404130/blue-lagoon3-entrance_t2j19d.jpg" alt="Blue Lagoon 3" class="rounded-lg shadow-md w-full h-[250px]" />
        </li>
        <li>
          <NuxtImg src="https://res.cloudinary.com/db2cje7en/image/upload/v1724404125/blue-lagoon3-2_kvrium.jpg" alt="Blue Lagoon 3" class="rounded-lg shadow-md w-full h-[250px]" />
        </li>
        <li>
          <NuxtImg src="https://res.cloudinary.com/db2cje7en/image/upload/v1724404111/Vang-Vieng-Blue-Lagoon-Jumping-platform_ibftxy.jpg" alt="Blue Lagoon 3" class="rounded-lg shadow-md w-full h-[250px]" />
        </li>
      </ul>
    </section>

    <!-- Activities Section -->
    <Card class="container mx-auto p-8 text-center bg-secondary text-secondary-foreground rounded-lg shadow-md">
      <h2 class="text-3xl font-semibold text-primary">
        Activities
      </h2>
      <p class="mt-4">
        Explore a range of activities at Blue Lagoon 3 including:
      </p>
      <ul class="mt-4 space-y-2 text-muted-foreground">
        <li>Jumping Platforms: Enjoy thrilling jumps from platforms approximately 10 to 15 meters high into the lagoon.</li>
        <li>Rope Swings: Experience the excitement of swinging out over the water before letting go and splashing down.</li>
        <li>Kayaking: Rent kayaks to explore the serene waters of the lagoon at your own pace.</li>
        <li>Rubber Tubes: Relax and float on rubber tubes, perfect for a leisurely day in the water.</li>
        <li>
          Cave Exploration: Visit nearby Phaboun Cave for a small trekking adventure and enjoy scenic views.
        </li>
        <li>Chill-Out Huts: Take a break in shaded huts scattered around the lagoon, ideal for relaxing and enjoying the surroundings.</li>
        <li>Food and Refreshments: Grab snacks and drinks from local vendors available at the lagoon.</li>
        <li>
          Small Waterfall: Enjoy the sight of a small waterfall located just outside the swimming area, adding to the natural beauty of the site.
        </li>
      </ul>
    </Card>

    <!-- Contact Section -->
    <Card class="container mx-auto p-8 shadow-md text-center">
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
    </Card>
  </div>
</template>

<style scoped>
/* Add additional styling here if needed */
</style>
