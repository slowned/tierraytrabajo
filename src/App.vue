<template>
  <div id="app">
    <header>
      <NavBar />
    </header>
    <body>
      <Hero />
      <AboutUs />
      <OurWorks />
      <CannabisSection />
      <ServicesSection />
      <Partners />
      <FooterSection />
    </body>
  </div>
</template>

<script>
import AboutUs from '@/components/AboutUs.vue'
import CannabisSection from '@/components/Cannabis.vue'
import FooterSection from '@/components/Footer.vue'
import Hero from '@/components/Hero.vue'
import NavBar from './components/NavBar.vue'
import OurWorks from '@/components/Works.vue'
// import OurProducts from '@/components/Products.vue'
import Partners from '@/components/Partners.vue'
import ServicesSection from '@/components/Services.vue'

export default {
  name: 'App',
  components: {
    AboutUs,
    CannabisSection,
    FooterSection,
    Hero,
    NavBar,
    OurWorks,
    Partners,
    ServicesSection,
  }
}
</script>

<style>
section {
  padding: 100px;
  padding-top: 50px;
}

.container h2 {
  text: center;
}
</style>
