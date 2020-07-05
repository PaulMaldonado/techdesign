<template>
  <div>
    <Navbar />
    <Banner />
    <Services />
    <Portafolio />
    <Footer />
  </div>
</template>

<script>
import Navbar from './components/Navbar';
import Banner from './components/Banner';
import Services from './components/Services';
import Portafolio from './components/Portafolio';
import Footer from './components/Footer';

export default {
  name: 'App',
  components: {
    Navbar,
    Banner,
    Services,
    Portafolio,
    Footer
  },
}
</script>

