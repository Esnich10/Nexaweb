<template>
  <div class="background-container">
    <!-- Aquí va tu contenido -->
    <Navbar />
  </div>
</template>

<script>
import Navbar from '../components/Navbar/Navbar.vue'

export default {
  components: {
    Navbar
  }
}
</script>

<style scoped>
.background-container {
  background-image: url('../assets/Background.svg');
  background-size: cover;
  background-repeat: no-repeat;
  background-position: center;
  min-height: 100vh;
}
</style>

