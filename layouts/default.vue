<template>
  <div>
    <Header />
    <p></p>
    <Nuxt />
    <p></p>
    <Footer />
  </div>
</template>

<script>
import Header from '../components/Header'
import Footer from '../components/Footer'

export default {
  components: {
    Header,
    Footer,
  },
  data() {
    return {
      items: [
        {
          title: 'Home',
          icon: 'home',
          to: {
            name: 'index',
          },
        },
        {
          title: 'Inspire',
          icon: 'lightbulb',
          to: {
            name: 'inspire',
          },
        },
      ],
    }
  },
}
</script>

<style>
@import '../assets/css/estilo.min.css';
</style>
