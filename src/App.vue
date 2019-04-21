<template>
  <div id="app">
    <SiteHeader/>
    <About/>
    <Portfolio/>
    <Contact/>
    <SiteFooter/>
  </div>
</template>

<script>
import SiteHeader from '@/components/SiteHeader'
import About from '@/components/About'
import Portfolio from '@/components/Portfolio'
import Contact from '@/components/Contact'
import SiteFooter from '@/components/SiteFooter'

export default {
  name: 'App',
  components: { SiteHeader, About, Portfolio, Contact, SiteFooter }
}
</script>

<style>
body {
  margin: 0;
}

#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

.content {
  font-size: 200%;
  padding: 200px 0;
}
</style>
