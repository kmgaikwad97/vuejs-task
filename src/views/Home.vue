<template>
  <div>
    <Banner />
    <TrustedByMany/>
    <LifeCycleCost/>
    <HealNaturally/>
    <Wellness/>
    <HealthPlan/>
    <Work/>
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
import Wellness from "../components/Wellness.vue";
import HealthPlan from "../components/HealthPlan.vue";
import Work from "../components/Work.vue";
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
    Wellness,
    HealthPlan,
    Offer,
    Dashboard,
    LifeCycleCost,
    Work
  },
};
</script>

<style>
</style>