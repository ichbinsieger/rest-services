<template>
  <div class="container" style="max-width: 95% !important;">
    <CThemeProvider>
      <CColorModeProvider #default="{ colorMode }">
        <CBox 
          font-family="body" 
          v-bind="mainStyles[colorMode]"
          as="section"
        >
          <CReset />
          <Header />
          <Nuxt />
          <Footer />
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
  CBox
} from '@chakra-ui/vue'

import Header from '@/components/Header'
import Footer from '@/components/Footer'

export default {
  name: 'App',
  components: {
    CThemeProvider,
    CColorModeProvider,
    CReset,
    CBox,
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
