<template>
  <v-app>
    <Header />
    <v-main>
      <!-- Hero section -->
      <HeroComponents />
      <!-- About Us -->
      <Aboutus />
      <!-- Portfolio -->
      <Portfolio />
      <!-- Project -->
      <Project />
      <!-- Gallery -->
      <Gallery />
      <!-- Contact -->
      <Contact />
      <!-- Footer -->
      <Footer />
    </v-main>
  </v-app>
</template>

<script>
import Header from "@/components/Header.vue";
import HeroComponents from "@/components/HeroComponents.vue";
import Aboutus from "@/components/AboutUs.vue";
import Portfolio from './components/Portfolio.vue';
import Project from './components/Project.vue';
import Gallery from './components/Gallery.vue';
import Contact from './components/Contactus.vue';
import Footer from './components/Footer.vue';
export default {
  name: "App",
  components: {
    Header,
    HeroComponents,
    Aboutus,
    Portfolio,
    Project,
    Gallery,
    Contact,
    Footer,
  },
};
</script>
