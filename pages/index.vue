<template>
  <div class="container">
    <Hero />
    <Services />
    <Contact />
    <About />
  </div>
</template>

<script lang="js">

import Hero from '~/components/Hero'
import Services from '~/components/Services'
import Contact from '~/components/Contact'
import About from '~/components/About'

export default {
  name: 'App',
  components: {
    Hero,
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
