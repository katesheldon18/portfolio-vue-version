<script>
import Homepage from './components/Homepage/Homepage.vue'
import About from './components/About/About.vue'

export default {
  components: {
    Homepage,
    About,
  },
  data: () => ({
    currentPage: "Home",
  }),
  methods: {
    showHomePage() {
      this.currentPage = "Home";
    },
    showAboutPage() {
      this.currentPage = "About";
    },
  },
};
</script>

<template>
  <div class="wrapper">
    <header>
      <nav class="nav">
        <a href="#" @click.prevent="showHomePage">Home</a>
        <a href="#" @click.prevent="showAboutPage">About</a>
      </nav>
    </header>
    <Homepage v-if="currentPage === 'Home'" />
    <About v-else />
  </div>


</template>