<template>
  <div class="">
    <Hero />
    <Values />
    <Banner
      title="Contact us today!"
      description="contact us now to find out if you meet the requirements to work with Rest Services."
      buttonText="Contact us"
    />
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
