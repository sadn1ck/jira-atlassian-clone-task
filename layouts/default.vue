<template>
  <div>
    <Navbar />
    <Nuxt />
    <Footer />
  </div>
</template>
<style>
html,
body {
  font-family: "Inter", sans-serif;
  background-color: white;
  transition: color 300ms, background-color 300ms;
}
.force-center {
  display: grid;
  place-items: center;
}
</style>
<script>
import Navbar from "~/components/base/Navbar";
import Footer from "~/components/base/Footer";
export default {
  components: {
    Footer,
    Navbar,
  },
};
</script>
