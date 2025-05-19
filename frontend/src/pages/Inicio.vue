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
              Creamos soluciones digitales innovadoras y personalizadas para
              impulsar tu negocio en el mundo digital. Descubre cómo podemos
              ayudarte a destacar y alcanzar tus metas.<br />
              ¡Tu éxito es nuestra prioridad!
            </p>

            <!-- Botones -->
            <div class="mt-4 d-flex gap-3">
              <button class="btn btn-danger fw-bold">AGENDA UNA DEMO</button>
              <button class="btn btn-dark fw-bold">VER PORTAFOLIO</button>
            </div>

            <!-- Tecnologías -->
            <div class="tech-icons mt-4 d-flex gap-4">
              <div>
                <i class="bi bi-check-circle-fill text-danger me-2"></i>React
              </div>
              <div>
                <i class="bi bi-check-circle-fill text-danger me-2"></i>Node JS
              </div>
              <div>
                <i class="bi bi-check-circle-fill text-danger me-2"></i
                >Microsoft Azure
              </div>
            </div>
          </div>

          <!-- Imagen a la derecha -->
          <div class="col-md-6 text-center mt-5 mt-md-0">
            <div class="mockup-container p-4 rounded-5">
              <img
                src="../assets/iphone-mockup.svg"
                alt="iPhone Mockup"
                class="img-fluid"
              />
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- Segunda Seccion -->
    <section class="pricing-section py-5 text-white">
      <div class="container">
        <!-- Título -->
        <div class="text-center mb-5">
          <h2 class="title-heading">
            Planes a la medida para
            <span class="highlight">todas las empresas.</span>
          </h2>
          <p class="subtitle-text mt-3">
            Te ofrecemos herramientas digitales únicas y asesoría especializada
            para llevar tu negocio al siguiente nivel. Estamos aquí para hacer
            que tu presencia en línea sea un éxito.<br />
            ¡Comencemos juntos este camino digital!
          </p>
        </div>

        <!-- Tarjetas -->
        <div class="row justify-content-center gap-4">
          <div class="col-md-3 card-box">
            <div class="card shadow pricing-card">
              <div class="card-body">
                <span class="text-danger fw-bold">Plan</span>
                <h4 class="card-title">Gratis</h4>
                <p>
                  El plan perfecto para estudiantes que desean crear su app.
                </p>
                <ul class="list-unstyled">
                  <li>
                    <i class="bi bi-check-circle-fill text-danger me-2"></i
                    >Lorem ipsum dolor
                  </li>
                  <li>
                    <i class="bi bi-check-circle-fill text-danger me-2"></i
                    >Lorem ipsum dolor
                  </li>
                  <li>
                    <i class="bi bi-check-circle-fill text-danger me-2"></i
                    >Lorem ipsum dolor
                  </li>
                </ul>
                <button class="btn btn-danger w-100 mt-3">
                  Agenda una demo
                </button>
              </div>
            </div>
          </div>

          <div class="col-md-3 card-box">
            <div class="card shadow pricing-card">
              <div class="card-body">
                <span class="text-danger fw-bold">Plan</span>
                <h4 class="card-title">Premium</h4>
                <p>
                  El plan perfecto para estudiantes y empresas que quieran crear
                  y manejar su página web.
                </p>
                <ul class="list-unstyled">
                  <li>
                    <i class="bi bi-check-circle-fill text-danger me-2"></i
                    >Lorem ipsum dolor
                  </li>
                  <li>
                    <i class="bi bi-check-circle-fill text-danger me-2"></i
                    >Lorem ipsum dolor
                  </li>
                  <li>
                    <i class="bi bi-check-circle-fill text-danger me-2"></i
                    >Lorem ipsum dolor
                  </li>
                </ul>
                <button class="btn btn-danger w-100 mt-3">
                  Agenda una demo
                </button>
              </div>
            </div>
          </div>

          <div class="col-md-3 card-box">
            <div class="card shadow pricing-card">
              <div class="card-body">
                <span class="text-danger fw-bold">Plan</span>
                <h4 class="card-title">Expert</h4>
                <p>
                  Garantizamos la eficiencia y continuidad de tus sistemas con
                  monitoreo y asistencia técnica inmediata.
                </p>
                <ul class="list-unstyled">
                  <li>
                    <i class="bi bi-check-circle-fill text-danger me-2"></i
                    >Lorem ipsum dolor
                  </li>
                  <li>
                    <i class="bi bi-check-circle-fill text-danger me-2"></i
                    >Lorem ipsum dolor
                  </li>
                  <li>
                    <i class="bi bi-check-circle-fill text-danger me-2"></i
                    >Lorem ipsum dolor
                  </li>
                </ul>
                <button class="btn btn-danger w-100 mt-3">
                  Agenda una demo
                </button>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
import Navbar from "../components/Navbar/Navbar.vue";

export default {
  components: {
    Navbar,
  },
};
</script>

<style scoped>
.background-container {
  background-image: url("../assets/Background.svg");
  background-size: cover;
  background-repeat: no-repeat;
  background-position: center;
  min-height: 100vh;
}
.pricing-section {
  background-image: url("../assets/Background.svg");
  background-size: cover;
  background-repeat: no-repeat;
  background-position: center;
  min-height: 100vh;
}

.text-highlight {
  color: #ff4b5c;
}

.pricing-card {
  background: linear-gradient(to bottom, #1f1f1f, #532f2f);
  border-radius: 1rem;
  color: white;
  padding: 20px;
  height: 100%;
  transition: transform 0.3s ease;
}

.pricing-card:hover {
  transform: translateY(-10px);
}

.card-box {
  flex: 1;
  max-width: 300px;
}
</style>
