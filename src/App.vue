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
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  /*text-align: center;*/
  color: #2c3e50;
  margin: 0; /* Remove default body margin */
  padding: 0; /* Remove default body padding */
}
</style>
