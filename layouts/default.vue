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

export default {
  name: 'App',
  components: {
    CThemeProvider,
    CColorModeProvider,
    CReset,
    CBox,
    Header,
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
