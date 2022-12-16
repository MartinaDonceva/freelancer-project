<template>
  <Navbar/>
  <Homepage/>
  <Portfolio/>
  <About/>
  <Contact/>
  <Footer/>
</template>

<style lang="scss">
</style>

<script>
import Homepage from "@/views/Homepage";
import Navbar from "@/components/Navbar";
import Portfolio from "@/components/Portfolio";
import About from "@/components/About";
import Contact from "@/components/Contact";
import Footer from "@/components/Footer";
export default {
  components: {
    Navbar,
    Homepage,
    Portfolio,
    About,
    Contact,
    Footer
  },

  name: 'app',
}
</script>