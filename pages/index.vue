<template>
  <div class="">
    <Hero />
    <Values />
    <Services />
    <div class="help-section">
      <Help class="counter-skew" />
      <Banner
        title="Get help today"
        description="We accept clients, male and female, aged 18 years and over with or without a local connection to Blackpool."
        buttonText="View Referrals"
        class="counter-skew"
      />
    </div>
    <Enquiry />
  </div>
</template>

<script lang="js">

import Hero from '~/components/Hero'
import Values from '~/components/Values'
import Banner from '~/components/Banner'
import Services from '~/components/Services'
import Help from '~/components/Help'
import Enquiry from '~/components/Enquiry'

export default {
  name: 'App',
  components: {
    Hero,
    Values,
    Banner,
    Services,
    Help,
    Enquiry,
  },
  data () {
    return {
    }
  },
  methods: {
  }
}
</script>

<style scoped>
  .help-section {
    background-color: #efefef;
    padding-top: 10px;
    padding-bottom: 35px;
    transform: skewY(-3deg);
  }

  .counter-skew {
    transform: skewY(3deg);
  }
</style>