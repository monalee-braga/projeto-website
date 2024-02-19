<template>
  <Header />
  <Home />
  <About />
  <Products />
  <Clients />
  <Contact />
  <Footer />
</template>

<script>
import Header from './components/Header.vue';
import Home from './components/Home.vue';
import About from './components/About.vue';
import Products from './components/Products.vue';
import Clients from './components/Clients.vue';
import Contact from './components/Contact.vue';
import Footer from './components/Footer.vue';

export default {
  name: 'App',
  components: {
    Header,
    Home,
    About,
    Products,
    Clients,
    Contact,
    Footer,
  },
};
</script>

<style></style>

