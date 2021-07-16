<template>
  <div class="container">
    <CThemeProvider>
      <CColorModeProvider>
        <CBox font-family="body" as="main">
          <CFlex>
            <CFlex position="fixed" top="1rem" right="1rem" align="center">
              <!--desktop content goes here -->
              <CFlex>
                <nuxt-link to="/">
                  <CButton as="a" variant="ghost" aria-label="Home" my="5" w="100%">Home</CButton>
                </nuxt-link>

                <nuxt-link to="/about">
                  <CButton as="a" variant="ghost" aria-label="About" my="5" w="100%">About</CButton>
                </nuxt-link>

                <nuxt-link to="/services">
                  <CButton as="a" variant="ghost" aria-label="Services" my="5" w="100%">Services</CButton>
                </nuxt-link>

                <nuxt-link to="/contact">
                  <CButton as="a" variant="ghost" aria-label="Contact" my="5" w="100%">Contact</CButton>
                </nuxt-link>
              </CFlex>
              <!--desktop content ends here -->
              <!--mobile content goes here -->
              <CFlex bgColor="gray.50" overflowY="auto" flexDir="column">
                <CFlex justify="flex-end">
                  <MenuAlt3Icon mt="2" mr="2" aria-label="Open Menu" />
                </CFlex>
                <CFlex flexDir="column" align="center">
                  <nuxt-link to="/">
                    <CButton as="a" variant="ghost" aria-label="Home" my="5" w="100%">Home</CButton>
                  </nuxt-link>

                  <nuxt-link to="/about">
                    <CButton as="a" variant="ghost" aria-label="About" my="5" w="100%">About</CButton>
                  </nuxt-link>

                  <nuxt-link to="/services">
                    <CButton as="a" variant="ghost" aria-label="Services" my="5" w="100%">Services</CButton>
                  </nuxt-link>

                  <nuxt-link to="/contact">
                    <CButton as="a" variant="ghost" aria-label="Contact" my="5" w="100%">Contact</CButton>
                  </nuxt-link>
                </CFlex>
              </CFlex>
              <!--mobile content ends here -->
              <MenuIcon aria-label="Open Menu" mr="2" />
              <CSwitch />
            </CFlex>
          </CFlex>
          <CReset />
          <Nuxt />
        </CBox>
      </CColorModeProvider>
    </CThemeProvider>
  </div>
</template>
<script>
import {
  CThemeProvider,
  CColorModeProvider,
  CReset,
  CBox,
  CFlex,
  CSwitch,
  CIconButton,
  CButton,
  CIcon,
} from '@chakra-ui/vue';

import { MenuIcon, MenuAlt3Icon } from "@vue-hero-icons/outline"

export default {
  name: 'App',
  components: {
    CThemeProvider,
    CColorModeProvider,
    CReset,
    CBox,
    CFlex,
    CSwitch,
    CIconButton,
    CButton,
    CIcon,
    MenuIcon, 
    MenuAlt3Icon,
  },
  inject: ['$chakraColorMode', '$toggleColorMode'],
  computed: {
    colorMode () {
      return this.$chakraColorMode()
    },
    theme () {
      return this.$chakraTheme()
    },
    toggleColorMode () {
      return this.$toggleColorMode
    }
  },
}
</script>
