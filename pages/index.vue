<template>
  <div class="container">
    <Hero />
    <Services />
    <Contact />
  </div>
</template>

<script lang="js">
import {
  CBox,
  CButton,
  CAvatarGroup,
  CAvatar,
  CAvatarBadge,
  CModal,
  CModalContent,
  CModalOverlay,
  CModalHeader,
  CModalFooter,
  CModalBody,
  CModalCloseButton,
  CIconButton,
  CFlex,
  CHeading
} from '@chakra-ui/vue'

import Hero from '~/components/Hero'
import Services from '~/components/Services'
import Contact from '~/components/Contact'

export default {
  name: 'App',
  components: {
    Hero,
    Services,
    Contact,
  },
  inject: ['$chakraColorMode', '$toggleColorMode'],
  data () {
    return {
    }
  },
  methods: {
  }
}
</script>
