<script setup>

</script>

<template>
  <div class="overflow-hidden flex flex-col min-h-screen">
    <TheHeader />
    <main class="flex-1">
      <slot />
    </main>
    <TheFooter />
  </div>
</template>
