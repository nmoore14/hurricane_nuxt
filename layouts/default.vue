<template>
  <div class="flex flex-col">
    <Navbar />
    <Hero />
    <nuxt />
  </div>
</template>

<script>
import Navbar from '~/components/Navbar'
import Hero from '~/components/Hero'

export default {
  components: {
    Navbar,
    Hero
  }
}
</script>

<style>
html {
  font-family: 'Source Sans Pro', -apple-system, BlinkMacSystemFont, 'Segoe UI',
    Roboto, 'Helvetica Neue', Arial, sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
  background-color: black;
}

*,
*:before,
*:after {
  box-sizing: border-box;
  margin: 0;
}
</style>
