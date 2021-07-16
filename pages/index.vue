<template>
  <div class="container">
    <Hero />
    <Services />
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

export default {
  name: 'App',
  components: {
    Hero,
    Services,
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
