<template>
  <div id="app">
    <AppHeader />
    <HeroSection />
    <!-- Restaurant Listing Component will come here -->
    <AppFooter />
  </div>
</template>

<script>
import AppHeader from './components/AppHeader.vue'
import AppFooter from './components/AppFooter.vue'
import HeroSection from './components/HeroSection.vue' // Make sure this is imported

export default {
  name: 'App',
  components: {
    AppHeader,
    AppFooter,
    HeroSection,
  },
}
</script>

<style>
/* Global styles for your app */
#app {
  display: flex;
  flex-direction: column;
  min-height: 100vh; /* Make the app take the full height of the viewport */
}

header {
  flex-shrink: 0; /* Prevents the header from shrinking */
}

.hero {
  flex-grow: 1; /* Make the hero section take up the remaining space */
}

footer {
  flex-shrink: 0; /* Prevents the footer from shrinking */
}
</style>
