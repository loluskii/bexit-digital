<template>
  <div>
    <div class="container">
    <Navbar />
    <div class="main">
      <nuxt/>
    </div>
  </div>
  <Footer />
  </div>

</template>

<script>
import Footer from '../components/Footer.vue'
import Navbar from '../components/Navbar.vue'
export default {
  components: { Navbar, Footer },

}
</script>

<style>

</style>
