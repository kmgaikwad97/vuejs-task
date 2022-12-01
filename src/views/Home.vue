<template>
  <div>
    <Banner />
    <TrustedByMany/>
    <HealNaturally/>
    <Offer/>
    <Dashboard/>
    <Footer />
  </div>
</template>

<script>
import Banner from "../components/Banner.vue";
import TrustedByMany from "../components/TrustedByMany.vue";
import HealNaturally from "../components/HealNaturally.vue";
import Offer from "../components/Offer.vue";
import Dashboard from "../components/Dashboard.vue";
import Footer from "./Footer.vue";
export default {
  name: "Home",
  components: {
    Banner,
    Footer,
    TrustedByMany,
    HealNaturally,
    Offer,
    Dashboard
  },
};
</script>

<style>
</style>