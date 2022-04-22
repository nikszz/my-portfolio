<template>
  <Header />
  <Section />
  <AboutMe />
  <Timeline />
  <Footer />
</template>

<script>
import Header from "./components/app-header.vue";
import Footer from "./components/app-footer.vue";
import Section from "./components/main-section.vue";
import AboutMe from "./components/about-me.vue";
import Timeline from "./components/time-line.vue";

export default {
  name: "App",
  components: {
    Header,
    Footer,
    Section,
    AboutMe,
    Timeline,
  },
};
</script>
