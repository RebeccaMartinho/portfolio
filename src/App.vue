<script setup>
import Welcome from './components/Welcome.vue'
import HeaderInfo from './components/Header.vue'
import About from './components/About.vue'
</script>

<template>
  <header class="bg-gray-800 text-white p-4">
    <HeaderInfo />
    </header>

  <main>
    <Welcome />
    <About />
  </main>
</template>

<style scoped>
header {
  line-height: 1.5;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

@media (min-width: 1024px) {
  /* header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  } */

  .logo {
    margin: 0 2rem 0 0;
  }

  /* header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  } */
}
</style>
