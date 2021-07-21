<template>
  <div class="">
    <Hero />
    <Values />
    <Banner />
    <Services />
    <Contact />
    <About />
  </div>
</template>

<script lang="js">

import Hero from '~/components/Hero'
import Values from '~/components/Values'
import Banner from '~/components/Banner'
import Services from '~/components/Services'
import Contact from '~/components/Contact'
import About from '~/components/About'

export default {
  name: 'App',
  components: {
    Hero,
    Values,
    Banner,
    Services,
    Contact,
    About,
  },
  data () {
    return {
    }
  },
  methods: {
  }
}
</script>
