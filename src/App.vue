<template>
  <Header />
  <Body />
  <Footer />
</template>

<script>
import Body from "./components/Body.vue";
import Footer from "./components/Footer.vue";
import Header from "./components/Header.vue";

export default {
  name: "App",
  components: {
    Header,
    Body,
    Footer,
  },
};
</script>

<style></style>
