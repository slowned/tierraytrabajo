<template>
  <div>
    <div class="hero">
      <div class="container">
        <div class="row">
          <div class="col-md-6 offset-md-6">
            <h1 class="display-6 text-complementary">Somos una cooperativa dedicada a la produccion de derivados del cannabis medicinal en Argentina.</h1>
          </div>
        </div>
      </div>
    </div>

    <div class="banner">
      <img
        src="@/assets/logos/tierraytrabajo-logo.png"
        alt="Logo de la Compañía"
        class="img-fluid banner-logo" />
    </div>
  </div>
</template>

<script>
export default {
  name: 'HeroComponent',
}
</script>

<style scoped>
.hero {
  position: relative;
  background-image: url('../assets/hero.jpg');
  background-size: cover;
  background-position: center;
  padding: 100px;

  /* width: 100%; */
  height: 77vh;
}

.banner {
  background-color: #75ab22;
  height: 15vh;
}

.banner-logo {
  padding-left: 30px;
  padding-top: 15px;
  padding-bottom: 15px;
  max-width: 100%;
  max-height: 100%;
}


.text-complementary {
  color: #75ab22; /* #fff Color de texto blanco */
  background-color: rgba(0, 0, 0, 0.6); /* Fondo translúcido */
  padding: 15px; /* Espaciado interno para el texto */
  border-radius: 10px; /* Bordes redondeados */
}
</style>
