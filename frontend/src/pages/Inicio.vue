<template>
  <div class="background-container">
    <!-- Aquí va tu contenido -->
    <Navbar />
    <section class="hero d-flex align-items-center min-vh-100">
    <div class="container">
      <div class="row align-items-center">
        <!-- Texto a la izquierda -->
        <div class="col-md-6 text-white">
          <h1>
            Somos expertos en la<br />
            <span class="text-highlight">creación de Web Apps</span>
          </h1>
          <p class="mt-3">
            ¡Bienvenido a Nexaweb!<br />
            Creamos soluciones digitales innovadoras y personalizadas
            para impulsar tu negocio en el mundo digital. Descubre cómo podemos ayudarte a destacar
            y alcanzar tus metas.<br />
            ¡Tu éxito es nuestra prioridad!
          </p>

          <!-- Botones -->
          <div class="mt-4 d-flex gap-3">
            <button class="btn btn-danger fw-bold">AGENDA UNA DEMO</button>
            <button class="btn btn-dark fw-bold">VER PORTAFOLIO</button>
          </div>

          <!-- Tecnologías -->
          <div class="tech-icons mt-4 d-flex gap-4">
            <div><i class="bi bi-check-circle-fill text-danger me-2"></i>React</div>
            <div><i class="bi bi-check-circle-fill text-danger me-2"></i>Node JS</div>
            <div><i class="bi bi-check-circle-fill text-danger me-2"></i>Microsoft Azure</div>
          </div>
        </div>

        <!-- Imagen a la derecha -->
        <div class="col-md-6 text-center mt-5 mt-md-0">
          <div class="mockup-container p-4 rounded-5">
            <img src="../assets/iphone-mockup.svg" alt="iPhone Mockup" class="img-fluid" />
          </div>
        </div>
      </div>
    </div>
  </section>
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

