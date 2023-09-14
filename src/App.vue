<template>
  <div>
    <Navbar />
    <Banner />
    <SectionOne />
    <SectionTwo />
    <SectionThree />
    <SectionFour />
    <Footer />
  </div>
</template>

<script>
import Navbar from "./components/Navbar.vue";
import Banner from "./components/Banner.vue";
import SectionOne from "./components/Section/SectionOne.vue";
import SectionTwo from "./components/Section/SectionTwo.vue";
import SectionThree from "./components/Section/SectionThree.vue";
import SectionFour from "./components/Section/SectionFour.vue";
import Footer from "./components/Footer.vue";

export default {
  name: "App",
  components: {
    Navbar,
    Banner,
    SectionOne,
    SectionTwo,
    SectionThree,
    SectionFour,
    Footer,
  },
};
</script>

<style scoped></style>
