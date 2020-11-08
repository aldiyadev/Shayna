<template>
  <div class="home">
    <Header />
    <Hero />
    <WomanShayna />
    <Instagram />
    <Partner />
    <Footer />
  </div>
</template>

<script>
import Header from "../components/Header";
import Hero from "../components/Hero";
import WomanShayna from "../components/WomanShayna";
import Instagram from "../components/Instagram";
import Partner from "../components/Partner";
import Footer from "../components/Footer";

export default {
  name: "Home",
  components: {
    Header,
    Hero,
    WomanShayna,
    Instagram,
    Partner,
    Footer,
  },
};
</script>
