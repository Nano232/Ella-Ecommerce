<template>
  <div class="home">
    <UpperBanner />
    <TheFeatures />
    <TopOffers />
  </div>
</template>

<script>
import UpperBanner from "@/components/home-page/UpperBanner.vue";
import TheFeatures from "@/components/home-page/TheFeatures.vue";
import TopOffers from "@/components/home-page/TopOffers.vue";
export default {
  name: "HomeView",
  components: {
    UpperBanner,
    TheFeatures,
    TopOffers,
  },
};
</script>
