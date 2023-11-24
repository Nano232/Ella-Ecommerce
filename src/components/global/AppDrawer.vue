<template>
  <div class="app-drawer">
    <v-navigation-drawer location="right" temporary v-model="drawer">
      <p>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Tempore,
        laboriosam ea. Nemo dolor quis dolorum laudantium nesciunt quidem
        doloremque blanditiis aut explicabo inventore earum sequi dicta, sit
        voluptatibus incidunt. Modi?
      </p>
    </v-navigation-drawer>
  </div>
</template>
<script>
export default {
  inject: ["Emitter"],
  data() {
    return {
      drawer: false,
    };
  },
  mounted() {
    this.Emitter.on("openCart", () => {
      this.drawer = !this.drawer;
    });
  },
};
</script>
