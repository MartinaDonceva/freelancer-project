<template>
  <Navbar/>
  <Homepage/>
  <Portfolio/>
  <About/>
  <Contact/>
</template>

<style lang="scss">
</style>

<script>
import Homepage from "@/views/Homepage";
import Navbar from "@/components/Navbar";
import Portfolio from "@/components/Portfolio";
import About from "@/components/About";
import Contact from "@/components/Contact";
export default {
  components: {
    Navbar,
    Homepage,
    Portfolio,
    About,
    Contact
  },

  name: 'app',
}
</script>