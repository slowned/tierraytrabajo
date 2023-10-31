<template>
  <section id="ourWork" class="works">
    <div class="container">
      <h2 class="text-center">Nuestro Trabajo</h2>
      <br>
      <b-row>
        <b-col md="6">
          <p>
            Empezamos desde la seleccion de semillas para poder seleccionar una madre bigorosa de la cual sacamos esquejes
            para propagar y asi trabajar con una planta sana y estable
          </p>
        </b-col>

        <b-col md="6">
          <b-carousel id="carousel"
            v-model="slide"
            fade
            :interval="2000"
            background="#ababab"
            img-width="1024"
            img-height="480"
            @sliding-start="onSlideStart"
            @sliding-end="onSlideEnd">

             <b-carousel-slide img-src="https://picsum.photos/1024/480/?image=52"> </b-carousel-slide>
             <b-carousel-slide img-src="https://picsum.photos/1024/480/?image=53"> </b-carousel-slide>
             <b-carousel-slide img-src="https://picsum.photos/1024/480/?image=54"> </b-carousel-slide>
             <b-carousel-slide img-src="https://picsum.photos/1024/480/?image=55"> </b-carousel-slide>

          </b-carousel>
        </b-col>

      </b-row>
    </div>
    
  </section>
</template>

<script>
export default {
  name: 'ourWorks',
  data() {
    return {
      slide: 0,
      sliding: null
    }
  },
  methods: {
    onSlideStart() {
      this.sliding = true
    },
    onSlideEnd() {
      this.sliding = false
    }
  }
}
</script>

<style scoped>
.works {
  background-color: #f8f8f8;
}

.image-style {
}
</style>
