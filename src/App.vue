<template>
  <div id="app" style="height: 100%;">
    <Landing />
    <About />
    <EDU />
    <Skills />
    <Projects />
    <Contact />
    <!--<About />
    <EDU />
    <Skills /> -->
  </div>
</template>
<script>
import Landing from "./components/Landing.vue";
import About from "./components/About.vue";
import Skills from "./components/Skills.vue";
/*import EDU from "./components/Education.vue";
import Skills from "./components/Skills.vue";*/
import EDU from "./components/EDU.vue";
import Projects from "./components/Projects.vue";
import Contact from "./components/Contact.vue";
export default {
  name: "App",
  components: {
    Landing,
    About,
    EDU,
    Skills,
    Projects,
    Contact,
    /*About,
    EDU,
    Skills*/
  },
};
</script>

<style lang="scss">
#app {
  font-family: Helvetica, Arial, sans-serif !important;
  -webkit-font-smoothing: antialiased !important;
  -moz-osx-font-smoothing: grayscale !important;
  text-align: center !important;
  color: #2c3e50 !important;
}
body,
html {
  width: 100%!important;
  height: 100%!important;
  font-size: 1rem !important;
  font-weight: 400 !important;
}

section {
  padding: 50px 0;
  overflow: hidden;

  h3 {
    text-transform: uppercase !important;
    font-weight: 600 !important;
    margin-bottom: 30px !important;
  }
}

ul {
  margin: 0;
  padding: 0;
  list-style-type: none;
}

a {
  color: black;

  &:hover {
    color: black;
    text-decoration: none !important;
  }
}

li {
  margin-bottom: 10px !important;
}
html {
  scroll-behavior: smooth;
}
@media (min-width: 768px) {
}
</style>
