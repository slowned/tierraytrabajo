<template>
  <section class="partners">
    <div class="container">
      <b-row justify="center">
        <b-col md="3">
          <img src="@/assets/partners/conicet.png" alt="conicet" class="partner-image">
        </b-col>
        <b-col md="3">
          <img src="@/assets/partners/inaes.png" alt="inaes" class="partner-image">
        </b-col>
        <b-col md="3">
          <img src="@/assets/partners/inase.png" alt="inase" class="partner-image">
        </b-col>
        <b-col md="3">
          <img src="@/assets/partners/unlp.png" alt="unlp" class="partner-image">
        </b-col>
      </b-row>
    </div>
  </section>
</template>


<script>
export default {
  name: 'PartnersSection',
}
</script>

<style scoped>
.partners {
  padding-top: 15px;
  padding-bottom: 15px;
}
.partner-image {
  max-width: 60%;
  height: auto;
  display: block;
  margin: 0 auto; /* Centra las imágenes horizontalmente */
}
</style>
