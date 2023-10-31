<template>
  <b-navbar toggleable="lg" type="light" variant="faded" class="navbar">
    <!-- Logo -->
    <b-navbar-brand to="/">
      <img
        src="@/assets/logos/tierraytrabajo-logo.png"
        alt="Logo de la Compañía"
        class="img-fluid logo-image" />
    </b-navbar-brand>

    <!-- Navbar toggle button for mobile -->
    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

    <!-- Navigation links -->
    <b-collapse id="nav-collapse" is-nav>
      <b-navbar-nav class="ml-auto">
        <b-nav-item href="#aboutUs">Nosotros</b-nav-item>
        <b-nav-item href="#ourWork">Nuestros Trabajos</b-nav-item>
        <b-nav-item href="#cannabis">Cannabis</b-nav-item>
      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
</template>

<script>
export default {
  name: 'NavBar',
}
</script>

<style scoped>
.navbar {
  height: 8vh;
  background-color: #f8f8f8;
}

.logo-image {
  max-width: 120px;
  padding-left: 30px;
}
</style>
