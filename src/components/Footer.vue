<template>
  <footer class="footer">
    <div class="container">
      <div class="row">
        <!-- Columna de contacto -->
        <div class="col-md-4">
          <h3>Contacto</h3>
          <p>
            <strong>Email:</strong> tierraytrabajo.cooperativa@gmail.com<br>
            <strong>Teléfono:</strong> (221) 456-7890
          </p>
        </div>

        <!-- Columna de redes sociales -->
        <div class="col-md-4 social-icons">
          <h3>Redes Sociales</h3>
          <ul class="list-unstyled">

            <li><a href="#">
             <b-icon class="social-icon" icon="instagram" ></b-icon>
            </a></li>
            <li><a href="#">
             <b-icon class="social-icon" icon="facebook" ></b-icon>
            </a></li>
            <li><a href="#">
             <b-icon class="social-icon" icon="youtube" ></b-icon>
            </a></li>
            <li><a href="#">
             <b-icon class="social-icon" icon="linkedin" ></b-icon>
            </a></li>
          </ul>
        </div>

        <!-- Columna del logo de la compañía -->
        <div class="col-md-4">
          <img
            src="@/assets/logos/tierraytrabajo-logo.png" 
            alt="Logo de la Compañía" 
            class="img-fluid footer-logo" />
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: 'footerSection',
}
</script>

<style scoped>
.footer {
  background-color: #75ab22;
  padding-top: 30px;
}

.footer-logo {
  max-width: 90%;
  max-height: 90%;
}


.social-icons ul {
  list-style: none;
  display: flex;
  padding: 0;
}

.social-icons li {
  margin-left: 10px;
}

.social-icon {
  font-size: 32px;
  color: black;
}



</style>
