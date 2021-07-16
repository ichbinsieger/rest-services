<template>
  <CBox as="nav" h="60px" px="4" d="flex" align-items="center" shadow="sm">
    <CLink
      as="nuxt-link"
      to="/"
      color="brand.700"
      font-weight="bold"
      :_hover="{ color: 'brand.900' }"
    >
      Rest Services
    </CLink>

    <CBox
      as="ul"
      color="gray.500"
      d="flex"
      align-items="center"
      list-style-type="none"
      ml="auto"
    >
      <CBox as="li" mr="8">
        <CLink
          as="nuxt-link"
          color="gray.500"
          :_hover="{ color: 'brand.400' }"
          is-esternal
          to="/about"
        >
          About
        </CLink>
      </CBox>
      <CBox as="li" mr="8">
        <CLink
          as="nuxt-link"
          color="gray.500"
          :_hover="{ color: 'brand.400' }"
          is-esternal
          to="/services"
        >
          Services
        </CLink>
      </CBox>
      <CBox as="li" mr="8">
        <CLink
          as="nuxt-link"
          color="gray.500"
          :_hover="{ color: 'brand.400' }"
          is-esternal
          to="/contact"
        >
          Contact
        </CLink>
      </CBox>
      <CBox as="li" mr="8">
        <CIconButton
          variant="ghost"
          variant-color="gray[900]"
          :aria-label="`Switch to ${
            colorMode == 'light' ? 'dark' : 'light'
          } mode`"
          :icon="colorMode == 'light' ? 'moon' : 'sun'"
          @click="$toggleColorMode"
        />
      </CBox>
    </CBox>
  </CBox>
</template>

<script>
import { CBox, CLink, CIconButton } from '@chakra-ui/vue'
export default {
  name: 'Header',
  inject: ['$chakraColorMode', '$toggleColorMode'],
  components: {
    CBox,
    CLink,
    CIconButton,
  },
  computed: {
    colorMode() {
      return this.$chakraColorMode()
    },
  },
}
</script>
