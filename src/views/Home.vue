<template>
  <div>
    <Banner />
    <TrustedByMany/>
    <HealNaturally/>
    <Footer />
  </div>
</template>

<script>
import Banner from "../components/Banner.vue";
import TrustedByMany from "../components/TrustedByMany.vue";
import HealNaturally from "../components/HealNaturally.vue";
import Footer from "./Footer.vue";
export default {
  name: "Home",
  components: {
    Banner,
    Footer,
    TrustedByMany,
    HealNaturally
  },
};
</script>

<style>
</style>