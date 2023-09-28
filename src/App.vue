<template>
  <Navbar/>
  <HeroSection/>
  <GallerySection/>
  <ContactSection/>
  <FooterSection/>
</template>

<script>
import Navbar from "./components/Navbar.vue"
import HeroSection from "./components/sections/HeroSection.vue";
import GallerySection from "./components/sections/GallerySection.vue";
import ContactSection from "./components/sections/ContactSection.vue";
import FooterSection from "./components/sections/FooterSection.vue";
export default {
  name: "App",
  components: { Navbar, HeroSection, GallerySection, ContactSection, FooterSection },
};
</script>

<style>
#app {
  font-family: "Bebas Neue", sans-serif;
  font-family: "Open Sans", sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
