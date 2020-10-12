<template>
  <div>
    <Header />
    <div class="centro">
      <h1>Teste de Projeto</h1>
    </div>
    <Nuxt />
    <card />
    <Footer />
  </div>
</template>

<script>
import Header from '../components/Header'
import Footer from '../components/Footer'
import card from '../pages/card'

export default {
  components: {
    Header,
    Footer,
    card,
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
