<script setup>
// import Homepage from './components/Homepage/Homepage.vue'
// import About from './components/About/About.vue'
</script>

<template>

  <div class="wrapper">
    <Homepage />
  </div>


  <main>
    <TheWelcome />
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
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}
</style>./components/Navigation/HelloWorld.vue./components/Homepage/HelloWorld.vue
