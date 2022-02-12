<template>
  <div>
    <Navbar/>
    <Home/>
    <About/>
    <Resume/>
    <Project/>
    <Skills/>
    <Testimonial/>
    <Contact/>
    <Footer/>
  </div>
</template>

<script>
import Navbar from './components/Navbar.vue'
import Home from './components/Home.vue'
import About from './components/About.vue'
import Project from './components/Project.vue'
import Skills from './components/Skills.vue'
import Testimonial from './components/Testimonial.vue'
import Contact from './components/Contact.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'app',
  components: {
    Navbar,
    Home,
    About,
    Project,
    Skills,
    Testimonial,
    Contact,
    Footer,
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
