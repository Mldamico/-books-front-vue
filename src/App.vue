<template>
  <div class="flex flex-col justify-between h-screen">
    <Header />
    <Body />
    <Footer />
  </div>
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
