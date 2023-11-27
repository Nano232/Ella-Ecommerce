<template>
  <div class="layout">
    <v-layout class="position-relative">
      <AppAavBar />
      <AppDrawer />
      <FixedNav />
      <v-main style="margin-top: 138px">
        <slot></slot>
      </v-main>
      <AppFooter />
    </v-layout>
  </div>
</template>

<script>
import AppAavBar from "./AppAavBar.vue";
import AppDrawer from "./AppDrawer.vue";
import AppFooter from "./AppFooter.vue";
import FixedNav from "./FixedNav.vue";
export default {
  data() {
    return {
      drawer: false,
    };
  },
  components: {
    AppAavBar,
    AppDrawer,
    AppFooter,
    FixedNav,
  },
};
</script>
