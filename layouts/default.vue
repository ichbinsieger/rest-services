<template>
  <div class="" >
    <Header />
    <Nuxt />
    <Footer />
  </div>
</template>
<script>

import Header from '@/components/Header'
import Footer from '@/components/Footer'

export default {
  name: 'App',
  components: {
    Header,
    Footer,
  },
  data() {
    return {
      mainStyles: {
        dark: {
          bg: 'gray.700',
          color: 'whiteAlpha.900'
        },
        light: {
          bg: 'white',
          color: 'gray.900'
        }
      }
    }
  },
}
</script>
<style>
  @import url('https://fonts.googleapis.com/css2?family=Courgette&display=swap');
  @import url('https://fonts.googleapis.com/css2?family=Carme&display=swap');

  .brand-text {
    font-family: 'Courgette', cursive !important;
    font-size: -webkit-xxx-large;
  }

  body {
    font-family: 'Carme', sans-serif !important;
  }

  .new-button {
    border-radius: 0 50px 50px 50px !important;
    padding: 0 50px;
    text-transform: uppercase;
    color: #056c5f;
  }

  .container {
    max-width: 99% !important;
  }

  .new-button:hover {
    border-color: white !important;
    background-color: transparent !important;
  }
</style>