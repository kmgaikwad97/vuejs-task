<template>
  <div>
    <Banner />
    <TrustedByMany/>
    <LifeCycleCost/>
    <HealNaturally/>
    <HealthPlan/>
    <Offer/>
    <Dashboard/>
    <Footer />
  </div>
</template>

<script>
import Banner from "../components/Banner.vue";
import TrustedByMany from "../components/TrustedByMany.vue";
import LifeCycleCost from "../components/LifeCycleCost.vue";
import HealNaturally from "../components/HealNaturally.vue";
import HealthPlan from "../components/HealthPlan.vue";
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
    HealthPlan,
    Offer,
    Dashboard,
    LifeCycleCost
  },
};
</script>

<style>
</style>