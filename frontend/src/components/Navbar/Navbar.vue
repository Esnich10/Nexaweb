<template>
  <div>
    <nav
      class="navbar navbar-expand-lg navbar-dark custom-navbar sticky-top shadow"
    >
      <div class="container">
        <router-link class="navbar-brand" to="/">Navbar</router-link>
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navbarNav"
          aria-controls="navbarNav"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
        <div
          class="collapse navbar-collapse justify-content-end"
          id="navbarNav"
        >
          <ul class="navbar-nav">
            <li class="nav-item">
              <router-link class="nav-link active" to="/">Inicio</router-link>
            </li>
            <li class="nav-item">
              <router-link class="nav-link" to="/nosotros"
                >Nosotros</router-link
              >
            </li>
            <li class="nav-item">
              <router-link class="nav-link" to="/servicios"
                >Servicios</router-link
              >
            </li>
            <li class="nav-item">
              <router-link class="nav-link fw-bold text-white" to="/contacto"
                >Contáctanos</router-link
              >
            </li>
          </ul>
        </div>
      </div>
    </nav>
  </div>
</template>

<script>
export default {};
</script>

<style>
.navbar {
  min-height: 70px;
}

.custom-navbar {
  background-color: #0a0a0a !important;
}

.custom-navbar .nav-link {
  color: white !important; /* o cualquier otro color como #ff4a4a */
}

.custom-navbar .nav-link:hover {
  color: #ff4a4a !important; /* color al pasar el mouse */
}
</style>
